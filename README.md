# curl-impersonate

由于目前 dockerhub 上官方还没有上传基于 bullseye 的镜像，只能自己构建，并修改 chrome dockerfile 的基础镜像为 python:3.10.9-slim-bullseye，为后续编译 pycurl 做准备，见 **pycurl-impersonate**

## 构建

`cd chrome && docker build -t curl-impersonate:0.5.3-chrome-slim-bullseye .`
