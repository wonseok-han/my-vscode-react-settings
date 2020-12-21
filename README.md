# my-vscode-react-settings

## .prettierrc

```
{
    "trailingComma": "es5",
    "tabWidth": 4,
    "semi": true,
    "singleQuote": true
}
```

`trailingComma`: 객체 또는 배열이 여러줄로 구성되어 있으면 맨 마지막 줄에 쉼표를 붙여줌.

`tabWidth`: 들여쓰기 크기 지정

`semi`: ;(세미콜론) 사용여부

`singleQuote`: 문자열 사용시 '' 또는 "" 지정. (true: '', false: "")

## jsconfig.json

```json
{
    "compilerOptions": {
        "baseUrl": "src"
    },
    "include": ["src"]
}
```

Source의 BaseUrl을 src로 설정.
