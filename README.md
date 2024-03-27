# Name

"docker_react"

# Features

react 用（node:20.10.0-bullseye-slim）のコンテナ

# Requirement

- docker

# Usage

### case1（GitHub から Clone）

1. コンテナをに繋ぐ
2. GitLab から任意の project を Clone する
3. ターミナルで"yarn"して packge.json の内容を install
4. ターミナルで"yarn dev"して立ち上げる

### case2(新しくプロジェクトを立ち上げる場合)

1. コンテナをに繋ぐ
2. ターミナルで"yarn create vite [project name] --template react-ts"
3. cd [project name] yarn vite@5.0.0で vite の version を固定
4. package.json の"dev": "vite"を"dev": "vite --host"に変更
5. ターミナルで"yarn dev"して立ち上げる

※case1 とファイル構成が異なるため 4.でフォルダの移動が必要な点を注意する

# Note

### vscode の設定

vscode プラグイン

- stylelint
- prettier-code formatter

# Author

- hiroshi muramatsu

# License
