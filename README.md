Vercelデプロイ用のレポジトリ。  
Pull requestsを通さないpushなどは禁止。  
このレポジトリからブランチを切ることは禁止。  
forkして使ってください。  

github右上のボタンから自分のレポジトリにfork。  
次にclone。  

```bash
git clone https://github.com/YOUR_NAME/YOUR_REPOSITORY.git
```

リモートレポジトリはこのようになっているはず。

```bash
$ git remote -v
origin  https://github.com/YOUR_NAME/YOUR_REPOSITORY.git (fetch)
origin  https://github.com/YOUR_NAME/YOUR_REPOSITORY.git (push)
```

このままだと上流レポジトリの反映が行えないため、これを upstream と言う名前でリモートに設定する

```bash
git remote add upstream https://github.com/Neginuko/haka-step-up.git
```

これで、上流レポジトリの反映も行えるようになる。
