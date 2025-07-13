# AviUtl2用データ同期ツール

AviUtl2のプラグインやスクリプトの管理が少し楽になるかもしれないツールです。

AviUtl2フォルダ内に作成する`Plugins`と`C:\ProgramData`配下の`Plugins`フォルダの状態を比較し、同期することができます。

これにより、ProgramDataを開かなくてもプラグインなどを追加する事ができます。

## 導入方法

1.  リリースページまたは`Code`ボタンから`Download ZIP`を押して、ファイルをダウンロードします。
  
    ![ダウンロードボタンの場所](https://github.com/user-attachments/assets/75d203ee-0a21-46ab-9cb7-fbb179601f90)

2.  ダウンロードしたZIPファイルを解凍し、中身をAviUtl2のディレクトリに移動します。移動後、同じ階層に`Plugins`フォルダを作成してください。

    ![フォルダ構成の例](https://github.com/user-attachments/assets/823b7e1a-52ff-4a9e-b998-188f6e79d2dd)

3.  `AviUtl2用データ同期ツール.exe`を右クリックし、`管理者として実行`を選択して起動します。


## 使い方

1.  `変更内容の比較`を押します。
2.  差分があった場合は、同期の方向を選びます。
    *   **ProgramDataに反映**: ローカル(`Plugins`フォルダ)の内容を`ProgramData`に上書きします。
    *   **ローカルに反映**: `ProgramData`の内容をローカル(`Plugins`フォルダ)に上書きします。
3.  コメント(任意)を入力して実行する。
4.  間違えた場合はバックアップ管理から復元してください。

<img width="702" height="632" alt="image" src="https://github.com/user-attachments/assets/a2c06bfe-8a8b-4cfe-90b8-6130f95e2320" />

## 既知のバグ

*   最終確認のダイアログボックスが画面の左上（座標 0,0）に表示される。
*   バグではないですが、AviUtl2フォルダ以外でも導入2の3つあれば機能はしますが、分かりやすいようにAviUtl2フォルダ内を推奨します。
