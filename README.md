"# ionic4-cordova-sample" 
Ionic4で新規アプリを作成したものを、cordovaを用いてAndroidアプリ（apkファイル）を作成するために作成したrepositoryです。

以下のコードにより作成しました。

```
ionic start ionic4-cordova-sample blank --type=angular
// Cordova? => Yes, Pro? => No
ionic cordova prepare android
// Platform android is not installed! Would you like to install it? => Yes
ionic cordova build android --prod
// これにより作成される、
// (C:\ionic4\)ionic4-cordova-sample\platforms\android\app\build\outputs\apk\debug\app-debug.apk
// を、Androidスマホにインストールすることができます。
```

詳細は以下

[Ionic4でCordovaでandroidアプリの作成](http://twosquirrel.mints.ne.jp/?p=28588)

[ionic4でのandroidアプリ開発環境](http://twosquirrel.mints.ne.jp/dokuwiki/doku.php/ionic4%E3%81%A7%E3%81%AEandroid%E3%82%A2%E3%83%97%E3%83%AA%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83)

## Requirement

- Node.js 8.12.0
- Ionic CLI 3.4.0


## Installation

    $ git clone https://github.com/adash333/ionic4-cordova-sample.git
    $ cd ionic4-cordova-sample
    $ npm install
    $ ionic serve

androidアプリの作成

    $ ionic cordova prepare android
    $ ionic cordova build android --prod


## Anything Else

WindowsでNode.jsのVersionをアップデートする方法については、以下を参考にしていただけますと幸いです。

http://twosquirrel.mints.ne.jp/?p=28131

## Author

adash333
