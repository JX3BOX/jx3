# 剑网3.com

## Dev
1. `npm install` 安装依赖
2. `npm run serve` 运行
3. 打开 http://localhost:5000/测试

## Deploy
```nginx
location / {
    try_files $uri $uri/ /index.html;
}
```