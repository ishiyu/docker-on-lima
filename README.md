# docker-on-lima

以下のサイトを参考に作った。

https://zenn.dev/matsukaz/articles/31bc31ff1c54b4

M1 mac で docker の Rails 環境を作れなかったため、lima で docker を動かしてみた。

## homebrew で必要な library を追加する

```sh
brew install lima
```

## lima の初回ダウンロード

```sh
cd docker-on-lima
limactl start docker-on-lima.yml
```

- Proceed with the default configuration
- Open an editor to override the configuration

の選択肢を聞かれるため、 `Proceed with the default configurationP を選択。

2回目以降は不要。

