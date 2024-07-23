# openapi generator
openapi generator: https://github.com/OpenAPITools/openapi-generator

cli install: https://openapi-generator.tech/docs/installation/

```
npm install
npm generate
```

## npm generate

```
"generate": "openapi-generator-cli generate -g typescript-axios -i ./src/schema/openapi.yml -o ./src/api"
```
-i : 스펙 파일 폴더 위치
-g: 사용할 제너레이터
-o: output 폴더
