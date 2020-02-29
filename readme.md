
# 构建镜像
1. 登录docker hub：docker login
2. 编写Dockerfile
3. 构建：docker build -t hhp/basic_deeplearning:v1 .

# 保存镜像
1. docker save -o hhp_basic_deeplearning_v1.tar hhp/basic_deeplearning:v1 

#使用镜像
1. docker load -i hhp_basic_deeplearning_v1.tar

# 推送镜像
1. 打标：docker tag local-image:tagname new-repo:tagname
2. 推送：docker push new-repo:tagname

