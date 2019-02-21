# shell if

- `-n`
  - `Non zero lenght` 文字列が空文字でないなら真を返す
- `-z`
  - `Zero lenght` 文字列が空なら真を返す

## サンプル

``` shell
if [ -n "$STR" ]; then
  echo "STR is not empty"
else
  echo "STR is empty"
fi
```

``` shell
if [ -z "$STR" ]; then
  echo "STR is empty"
else
  echo "STR is not empty"
fi
```