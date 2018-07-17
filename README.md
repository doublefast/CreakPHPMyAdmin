# 简介

Python3实现挂载字典爆破PHPMyAdmin，虽然目前速度不是很快，但还是可以使用的。

这个脚本测试的`PHPMyAmin`是在`PHPStudy`软件自带的，其他版本可能会有些差异，具体以实际为准，至于爆破的速度~ 由于本人多线程这块暂时不是很熟悉，理解万岁~理解万岁~~

![](http://image.3001.net/images/20180717/1531819233472.png)  

# 依赖安装

到项目下使用`pip`来安装相关依赖

```shell
cd CreakPHPMyAdmin/
pip install -r requirements.txt
```

# 使用方法

`--url`：爆破的url地址

`--user`：爆破的用户名

`--pass`:爆破字典所在的路径地址

```r
Usage: creakmysql.py -h | --help

Options:
  -h, --help       show this help message and exit
  --url=URL        target url  usage: -url http://www.xxx.com/phpmyadmin
  --user=USERNAME  username   usage: --user root
  --pass=PASSWORD  password path   usage: --pass /sqlsec/password.txt
```

# 使用效果
本次测试的环境是phpstudy下的phpmyadmin，目前就爆破的速度来看有点慢，但再慢也是比手工输入要快的😁 希望自己后期学了多线程后可以提高爆破的速度。
![](http://image.3001.net/images/20180709/15311358833281.png)  