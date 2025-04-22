# MLAA.dctl

## 概要

このプロジェクトは、Morphological Anti-Aliasing (MLAA) をDaVinci Resolve向けのDCTL（DaVinci Color Transform Language）に移植したものです。
<table>
<tr>
<td><img src="https://github.com/user-attachments/assets/1994521a-a6ba-4675-bc9f-295a5878aaf0" alt="Original"></td>
<td><img src="https://github.com/user-attachments/assets/3aa4a962-4fba-4cd4-b62f-e55be5cdb536" alt="MLAA Applied"></td>
</tr>
<tr>
<td align="center">Before</td>
<td align="center">After</td>
</tr>
</table>

## 特徴

- MLAAをDCTLで実装し、アンチエイリアシング効果を提供します。
- オリジナルコードはAMDのMLAA11プロジェクトから取得しています（[参考1](https://github.com/GPUOpen-LibrariesAndSDKs/MLAA11)）。
- GLSLへの移植コードを参考にしています（[参考2](https://www.shadertoy.com/view/cllXRB)）。

## インストール方法

1. `MLAA.dctl`ファイルを取得します。
2. DaVinci ResolveのDCTLフォルダに`MLAA.dctl`をコピーします。

   - Windowsの場合: `C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT\`
   - macOSの場合: `/Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT/`

## 使用方法

1. DaVinci Resolveでプロジェクトを開きます。
2. カラーページで新しいノードを追加し、DCTLエフェクトを適用します。
3. `MLAA.dctl`を選択します。
4. （`ShowEdgesOnly`はデバッグ用なのでチェックは外してください。）

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。
