## 说明

- 用于小文件访问（20M以内）；
- 访问方式：
  - 确定需要访问的文件，比如： “/favicon.ico” ；
  - 配合国内CDN域名加速： `https://cdn.jsdelivr.net/gh/cnyasin/file@main` ；
    - `https://cdn.jsdelivr.net`：CDN域名；
    - `/gh`：GitHub；
    - `/cnyasin/file`：GitHub用户名/仓库名；
    - `/@main`：main分支；
  - 最终的CDN访问链接： “https://cdn.jsdelivr.net/gh/cnyasin/file@main/favicon.ico” ；
