# github の使い方メモ
#### 間違ってたら Pull Request してー  
  
> git init \# git の初期化  
>  
> git config --global user.name "chu2"  
> git config --global user.email "見せられないよ！"  
>  
> git config github.user "chu2"  
> git config github.token "APIトークン"  
> \# APIトークンは[ここ](https://github.com/account/admin)に書いてある  
>  
> git config --list \# 設定の確認  
>  
> touch README.md  
> \# 拡張子をmdにすることでMarkdownが使える！  
> \# Markdownについては[ここ](http://ja.wikipedia.org/wiki/Markdown)  
>  
> git add README.md  
> git commit -m "こみっとー"  
>  
> git remote add origin git@github-chu2:chu2/buchu.git  
> git push origin master