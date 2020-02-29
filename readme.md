
# 构建镜像
1. 编写Dockerfile
2. 构建：docker build -t hhp/basic_deeplearning:v1 .

# 推送镜像
1. 登录docker hub：docker login
2. 打标：docker tag local-image:tagname new-repo:tagname
3. 推送：docker push new-repo:tagname

