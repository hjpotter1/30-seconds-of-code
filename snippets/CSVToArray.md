---
title: CSVToArray
tags: string,array,intermediate
---

Converts a comma-separated values (CSV) string to a 2D array.

- Use `Array.prototype.slice()` and `Array.prototype.indexOf('\n')` to remove the first row (title row) if `omitFirstRow` is `true`.
- Use `String.prototype.split('\n')` to create a string for each row, then `String.prototype.split(delimiter)` to separate the values in each row.
- Omit the second argument, `delimiter`, to use a default delimiter of `,`.
- Omit the third argument, `omitFirstRow`, to include the first row (title row) of the CSV string.

```js
const CSVToArray = (data, delimiter = ',', omitFirstRow = false) =>
  data
    .slice(omitFirstRow ? data.indexOf('\n') + 1 : 0)
    .split('\n')
    .map(v => v.split(delimiter));
```

```js
CSVToArray('a,b\nc,d'); // [['a', 'b'], ['c', 'd']];
CSVToArray('a;b\nc;d', ';'); // [['a', 'b'], ['c', 'd']];
CSVToArray('col1,col2\na,b\nc,d', ',', true); // [['a', 'b'], ['c', 'd']];
```















#### 職務要約

2016年9月、羽石株式会社に入社し、現在に至るまで同社でシステムエンジニアとして勤務しております。主にJavaScript、CSS、Javaを用いたECサイト、精算システム、旅行関連サービスのシステム開発に約7年間携わってきました。この期間、要件定義に基づく設計から開発、テストに至るまでの一連の上流工程を経験し、一貫してプロジェクトを推進してきました。
エンジニアとして、クライアント及びユーザーのニーズを深く理解し、それに基づく適切な技術提案と計画立案に長けています。新技術の習得に積極的であり、特にフロントエンド開発では、React、Vue.js、TypeScriptなどの主流技術に注力し、最新の技術トレンドを追いながら複雑なビジネス要求に対応する能力を有しています。更なるスキルアップと新技術への接触を目指し、SESから自社サービス企業への転職を検討しており、キャリアのさらなる向上を望んでいます。
東京都、神奈川県、埼玉県での勤務を希望しています。



常駐先は半年から1年程度で変わり、その都度、業務内容や技術も変わります。案件の選択に自由がないため、古い技術やフレームワークの使用も多いです。プログラミングだけでなく、設計書の作成なども主な業務になることがあります。フロントエンドの主流技術（React、Vue.js、TypeScriptなど）に集中し、スキルアップと新しい技術に触れる環境を求めています。そのため、転職を考えています。



### 面接質問

#### 自己紹介

本日は貴重なお時間をいただき、誠にありがとうございます。○○○（名前）と申します。○○大学大学院○○専攻で学位取得後、○○会社にて、○○（職種）として○年間従事してまいりました。主に○○（職務内容）を担当しており、○○（力を入れた点）を行った結果、○○（実績）に達成することができました。このような経験が貴社でも活かせると考え、応募いたしました。本日はどうぞよろしくお願いいたします。

2016年9月に羽石株式会社（SES企業）に入社し、現在も在籍しています。約7年間、JavaScript、TypeScript、CSS、Javaなどの言語を使用して、ECサイト、決算、旅行などの客先常駐プロジェクトに関わり、要件定義に基づく設計などの上流工程から、開発やテストまでを一貫して担当しています。

#### 技術

###### Reactコンポーネントのデザイン

Reactコンポーネントのデザイン経験（単一責任の原則など）やReactとReduxを使用した開発設計の経験があります

typescript

静的型付け、￥コードを実行する前、コンパイルの段階でエラーの検出ができるように改良されました。これによって、プログラムの動作がより安定します。　大規模

長期的なプロジェクトのメンテナンスが容易になります。

多くのモダンな開発ツールやライブラリがTypeScriptの利用を前提に設計されています。これにより、より堅牢な開発環境を構築することができます。

###### Tailwind、CSS-in-JS

#### 職務経歴紹介

###### 最好的项目

ses送信，cognit之类都是我率先开发。
