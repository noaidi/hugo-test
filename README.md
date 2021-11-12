# Hugo

[Install Hugo](https://gohugo.io/getting-started/installing/)

----

## Homebrew
https://github.com/homebrew/install

### `brew` 제거
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/uninstall.sh)"
```

### `brew` 설치
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
##### *~/.bashrc* 수정
``` sh
# homebrew
eval "$(/opt/homebrew/bin/brew shellenv)"
```

----

## Hugo 설치

```sh
brew install hugo
```
###### Hugo 업그레이드

```sh
brew upgrade hugo
```

----

### 프로젝트 생성
```sh
mkdir PROJECT
cd PROJECT
hugo new site .
```

###### 확인하기
```sh
hugo server
```