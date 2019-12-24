# Boostnoteのダウンロード
https://boostnote.io/

# Google Driveのダウンロード
google driveをdropboxのように使う必要があるので, 会社のアカウントgoogle driveをpcの任意の場所にマウントしておく.(pcのフォルダ操作でgoogle drive上のファイルを触れるようにしておく)

シークレットモードのブラウザでgoogle driveをダウンロード.(https://www.google.com/intl/ja_ALL/drive/download/)

![2019-12-20_14 22 32](https://user-images.githubusercontent.com/33983800/71232386-1f161080-2335-11ea-80dc-cc4f94121e32.png)

:point_up: こんな感じになるので会社のアカウントでログイン.

画像とかの同期の設定はとりあえずチェック外して任意の場所の任意のフォルダを共有場所として設定する.(:point_up_2:でいう"マウント")

macだとこんな感じでFinderでGoogle Driveのマイドライブが開ければOK

<img width="763" alt="スクリーンショット 2019-12-20 14 25 56" src="https://user-images.githubusercontent.com/33983800/71232560-c5621600-2335-11ea-8333-41ace47855b2.png">




## Ubuntuはこれ
https://mogi2fruits.net/blog/os-software/linux/ubuntu/4263/

自動起動設定の実行コマンドに以下を入力する
/usr/bin/google-drive-ocamlfuse /home/ユーザー名/GoogleDriveをマウントしたディレクトリ名

# Google Driveの共有フォルダをマイドライブと同期する
会社のGoogle Drive共有アイテム(_member/)にBoostnoteフォルダがあるので右クリックして"マイドライブに追加"をクリック

<img width="312" alt="スクリーンショット 2019-12-21 14 10 42" src="https://user-images.githubusercontent.com/33983800/71303423-ceb5b600-23fb-11ea-8aa2-f089325d8549.png">


Google Drive側の設定はこれでOK

# Storage Locationの追加
Ctrl + ,(⌘ + ,)で設定を開き, "ストレージ"から"ストレージロケーションを追加"をクリック.

名前を"Amazing engin Domestic WIKI"(個々人のBoostnoteアプリに紐付いているだけの名前なので何でも良い)にする.

![Screenshot from 2019-12-20 13-46-47](https://user-images.githubusercontent.com/33983800/71231671-50d9a800-2332-11ea-93a5-566141781a3f.png)

保存場所を先程Google Driveをマウントしたディレクトリ内のBoostnoteディレクトリに指定する.

![Screenshot from 2019-12-20 13-46-32](https://user-images.githubusercontent.com/33983800/71231658-4c14f400-2332-11ea-82cf-e61b408c53df.png)

これで以下のように表示されたらOK

![Screenshot from 2019-12-20 13-51-42](https://user-images.githubusercontent.com/33983800/71231674-5505c580-2332-11ea-88d3-cf2f10a5f4d6.png)

:warning: 画像を貼る場合は画像を先程のBoostnoteディレクトリ内に入れないと共有されないので注意
