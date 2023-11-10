## What is this??
- 有価証券報告書の"３【事業等のリスク】"から非財務情報をスクレイピングします。
- 使う場合は任意の有価証券報告書をダウンロードしてきます（手動で）。
	- 有報の自動収集ツールは面倒なので作りません。。

## 仕様
- サンプルとして、EDINETからダウンロードしたJALの有報をセットしてあります。（JALフォルダにあります）

- 「0102010_honbun_jpcrp030000-asr-001_E04272-000_2023-03-31_01_2023-06-26_ixbrl.htm」
	- 非財務情報が含まれています(分かりやすいようにカレントディレクトリに対象のhtmファイルを持ってきてます)

- 「app.ipynb」で、任意のhtmファイルからテキスト(３【事業等のリスク】)を抽出します。
- 抽出したテキストは、「output.txt」として保存される仕組みなっています