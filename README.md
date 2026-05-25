```sh
export url="https://github.com/asano69/my-images/blob/main/sample/test.jpg"

echo "$url" \
| sed 's#https://github.com/#https://cdn.jsdelivr.net/gh/#' \
| sed 's#/blob/#@#'
```
