
# _ng5-material-checkbox-demo_ Angular Materialを利用するためのAngular5用初期セットプロジェクト
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)


_ng5-material-checkbox-demo_ はAngular5でAngular Meterialを利用したいと考えているプログラマのための簡単初期設定プロジェクトです。

_ビデオ解説_
<https://youtu.be/ttLh47qv9pk>

_全ソース_
<https://github.com/Ohtsu/ng5-material-checkbox-demo>

## 概要 
    
まず、以下の _Angular Material_ サイトの_Getting started_ ページを参照してください。 
    
<https://material.angular.io/guide/getting-started>
 
本プロジェクトは、このページで解説されている手順に基づいています。 

以下の _Step_ 番号はこのページの _Step_ 番号に対応しています。ただし、_step_ 3については、含まれていません。これは必要とされる _Agular Material_ のモジュールによって変化するからです。

### インストール設定されたライブラリおよび設定 

   - @angular/material (Step 1)

   - @angular/cdk (Step1)

   - @angular/animations ('src/app/app.module.ts' ファイルの修正を含む) (Step2)

   - デフォルト・テーマ(indigo.pink.css)のstyles.cssファイルへの追加 (step4)

   - hammerjs ('src/main.ts'ファイルの変更を含む) (step5)

   - 公式のMaterial Design Iconsの追加 ('index.html'ファイルの変更) (Step6) 


 もちろん、インストールするライブラリなどについては以下のような _Package.json_ ファイルの内容を変更することによって構成を変えることができます。

```bash

  "dependencies": {
    "@angular/animations": "^5.0.1",
    "@angular/cdk": "^5.0.0-rc0",
    "@angular/common": "^5.0.0",
    "@angular/compiler": "^5.0.0",
    "@angular/core": "^5.0.0",
    "@angular/forms": "^5.0.0",
    "@angular/http": "^5.0.0",
    "@angular/material": "^5.0.0-rc0",
    "@angular/platform-browser": "^5.0.0",
    "@angular/platform-browser-dynamic": "^5.0.0",
    "@angular/router": "^5.0.0",
    "core-js": "^2.4.1",
    "gulp": "^3.9.1",
    "hammerjs": "^2.0.8",
    "rxjs": "^5.5.2",
    "zone.js": "^0.8.14"
  },
  "devDependencies": {
    "@angular/cli": "1.5.0",
    "@angular/compiler-cli": "^5.0.0",
    "@angular/language-service": "^5.0.0",
    "@types/jasmine": "~2.5.53",
    "@types/jasminewd2": "~2.0.2",
    "@types/node": "~6.0.60",
    "codelyzer": "~3.2.0",
    "jasmine-core": "~2.6.2",
    "jasmine-spec-reporter": "~4.1.0",
    "karma": "~1.7.0",
    "karma-chrome-launcher": "~2.1.1",
    "karma-cli": "~1.0.1",
    "karma-coverage-istanbul-reporter": "^1.2.1",
    "karma-jasmine": "~1.1.0",
    "karma-jasmine-html-reporter": "^0.2.2",
    "protractor": "~5.1.2",
    "ts-node": "~3.2.0",
    "tslint": "~5.7.0",
    "typescript": "~2.4.2"
  }


```

## 必要環境

   - Git
   - Node.js
   - TypeScript2
   - Angular5
   - Angular/cli



## インストール方法

このプログラムをインストールするには:

   - まずインストール用のディレクトリを作成し、その中に入ります。

```bash
$ mkdir mydir
$ cd mydir
```
   - 以下のように _Git_ によりクローンを作成します。

```bash
$ git clone https://github.com/Ohtsu/ng5-material-checkbox-demo.git
```

   -  _ng5-material-checkbox-demo_ ディレクトリに入り、"npm install"を実行します。

```bash
$ cd ng5-material-checkbox-demo
$ npm install 
```


#### プログラムのチェック

インストールが終了しましたら、この段階でプログラムの稼働をチェックします。以下のようにローカルサーバを起動し、ブラウザから **http://localhost:4200** にアクセスし、Angularの初期画面が表示されるかをチェックします。


```bash
$ ng serve
```

  - ***初期画面*** 

  <img src="https://raw.githubusercontent.com/Ohtsu/images/master/ng5-i18n-demo/ng5-i18n-demo_en-page_01.png" width= "640" >
 

#### ローカルサーバの停止

ローカルサーバを停止するには、コマンドラインから **Ctrl+C** と打ち、メッセージが出てきましたら、**y+Return** で停止します。




## バージョン

   - ng5-material-checkbox-demo : 0.1
   - Angular5     : 5.0.0
   - @angular/cdk : 5.0.0-rc0
   - @angular/material : 5.0.0-rc0,
   - hammerjs : 2.0.8
   - @angular/cli : 1.5.0



## 参考文献

- "Agular Material Getting started",
<https://material.angular.io/guide/getting-started>



## 変更履歴

 - 2017.11.15  version 0.1.1 アップロード


## 著作権

copyright 2017 by Shuichi Ohtsu (DigiPub Japan)


## ライセンス

MIT © [Shuichi Ohtsu](ohtsu@digipub-net.com)


