# unzip_files_script

## What's is this for ? 
- zipファイルが大量にある場合に手動で解凍するのがしんどい。

## Usage
```
sh automatically_unzip_files.sh
```

## Condition for this ...
このプログラムでいう`dataFiles`に任意のzipファイルが入っていること。

## Flow
`dataFiles`ディレクトリに移動し、１つずつzipファイルを解凍していきます。  
その際に、zipファイルも消します。  
残したい場合は、[18行目](https://github.com/uewolf25/unzip_files_script/blob/main/automatically_unzip_files.sh#L18)をコメントアウトして使いましょう。

