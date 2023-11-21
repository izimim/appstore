# Appstore
自用 [1Panel](https://1panel.cn/) 应用适配库

## Usage
1panel 计划任务类型 Shell 脚本的计划任务框里，添加并执行以下命令，或者终端运行以下命令:
```shell
rm -rf /opt/1panel/resource/apps/local/*

git clone https://github.com/izimim/appstore.git /tmp/appstore 

cp -rf /tmp/appstore/apps/* /opt/1panel/resource/apps/local/

rm -rf /tmp/appstore
```