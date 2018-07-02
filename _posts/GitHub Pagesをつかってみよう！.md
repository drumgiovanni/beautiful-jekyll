---
layout: post
published: true
title: 'GitHub Pagesをつかってみよう！'
subtitle: 無料、広告無し、自由にカスタマイズ
tags: html css javascript impress.js github-pages github
---
## GitHub Pagesとは  


GitHubが提供している、**静的Webサイトを無料で公開することができるサービス**です。  

GitHubのアカウントに紐付けられる**ユーザーサイト**と、GitHubリポジトリに紐付けられる**プロジェクトサイト**を作成することが可能です。  

詳しくは[公式ページ](https://pages.github.com/)を確認してください。  


今回は、**ユーザサイト**の作り方を紹介します！  


## 手順  

- リポジトリを作成する

	GitHubにログインし、＋（下記画像参照）を押し、新規リポジトリを作成してください。  
    
    ![ghp1.png]({{site.baseurl}}/img/blogpics/ghp1.png)  
    
	新規リポジトリの名前は、`{USERNAME}.github.io`としてください。こうしないと、githubがリポジトリをユーザーサイトだと認識してくれません！  
    
	![ghp2.png]({{site.baseurl}}/img/blogpics/ghp2.png)  
　　　　　　　　　　　　　　　　　　　　　　　　　　　　  (github pages 公式サイトより)
    
    


- リポジトリをローカルにcloneする  

	ターミナルを開いて、 `git clone https://github.com/{USERNAME}/{USERNAME}.github.io` と入力すると、リポジトリがクローンされる。  
    ターミナルで、 `cd {USERNAME}.github.io` と入力しディレクトリを移動。 `{USENAME}.github.io`以下にWebページとしてデプロイしたいコンテンツを配置する。  
    
    
- リポジトリをpushしてデプロイ！  

```
git add -A
git commit -m "init"
git push origin master
```

これで`{USERNAME}.github.io`の中身がhttps://{USERNAME}.github.io に公開されているはずです！  
とても簡単！  

## 最後に  

[僕のホームページ](https://drumgiovanni.github.io)もGitHub Pagesのユーザーページと、[以前の記事](https://drumgiovanni.github.io/blog/2018-06-24-html-css/)で紹介したImpress.jsを使って作られています！  
**広告もなく、自分の自由自在にページを作ることができる**ので、興味がある方はぜひチャレンジしてみてください〜〜〜

