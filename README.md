# my-vscode-react-settings

## .prettierrc

```
{
  "trailingComma": "es5",
  "tabWidth": 2,
  "semi": true,
  "singleQuote": true,
  "printWidth": 80,
  "useTabs": false,
  "arrowParens": "avoid",
  "bracketSpacing": false,
  "overrides": [
    {
      "files": "*.json",
      "options": {
        "printWidth": 200
      }
    }
  ]
}
```

`trailingComma`: 객체 또는 배열이 여러줄로 구성되어 있으면 맨 마지막 줄에 쉼표를 붙여줌.

`tabWidth`: 들여쓰기 크기 지정

`semi`: ;(세미콜론) 사용여부

`singleQuote`: 문자열 사용시 '' 또는 "" 지정. (true: '', false: "")

`printWidth`: 줄 바꿈 할 폭 길이

`useTabs`: 탭 사용 여부

`arrowParens`: 화살표 함수 괄호 사용 방식

`bracketSpacing`: 객체 리터럴에서 괄호에 공백 삽입 여부 

`overrides`: 특정 파일별로 옵션을 다르게 지정함, ESLint 방식 사용

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
