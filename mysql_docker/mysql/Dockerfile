# 使用镜像
FROM mysql:5.7.42
# 暴露端口
EXPOSE 3306
# 加入mysql设置文件
ADD ./my.cnf /etc/mysql/conf.d/my.cnf
# docker run 执行命令
CMD ["mysqld"]
