## 과정
1. 오버워치 기존 프로젝트 복사
1. npm init -y
1. npm i parcel-bundler
1. main.css ->main.scss로 확장자명 변경

1.
```
package.json
  "scripts": {
    //"test": "echo \"Error: no test specified\" && exit 1"
   
    "dev" : "parcel index.html",
    "bulid": "parcel bulid index.html"
  
  },

```
6. 서버 띄우기 : npm run dev
