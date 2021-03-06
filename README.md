# 2020-Maritime-Website-Training
## 2020 海运网站实训
|  |星期一|星期二|星期三|星期四|星期五|
| --- | --- | --- | --- | --- | --- |
|  | 9月7日|9月8日|9月9日|9月10日|9月11日|
|1-2|8:10-9:30|8:10-9:30|8:10-9:30|8:10-9:30|8:10-9:30|8:10-9:30|
|3-4|9:50-11:10|9:50-11:10|9:50-11:10|9:50-11:10|9:50-11:10|
|5-6|  |13:30-14:50|13:30-14:50|13:30-14:50|  |
|7-8|  |15:00-16:20|15:00-16:20|15:00-16:20|  |
|  | 9月14日|9月15日|9月16日|9月17日|9月18日|
|1-2|8:30-9:50|8:30-9:50|8:30-9:50|8:30-9:50|8:30-9:50|
|3-4|10:10-11:30|10:10-11:30|10:10-11:30|10:10-11:30|10:10-11:30|
|5-6|  |13:40-15:00|13:40-15:00|13:40-15:00|  |
|7-8|  |15:10-16:30|15:10-16:30|15:10-16:30|  |
|  |  |  |  |  |  |
|  | 9月21日|9月22日|9月23日|9月24日|9月25日|
|1-2|8:10-9:30|8:10-9:30|8:10-9:30|8:10-9:30|8:10-9:30|8:10-9:30|
|3-4|9:50-11:10|9:50-11:10|9:50-11:10|9:50-11:10|9:50-11:10|
|5-6|  |13:30-14:50|13:30-14:50|13:30-14:50|  |
|7-8|  |15:00-16:20|15:00-16:20|15:00-16:20|  |
|9-10|  |  | 18:00-19:20 |  |  |
|  | 9月28日|9月29日|9月30日|10月1日|10月2日|
|1-2|8:30-9:50|8:30-9:50|8:30-9:50|  |8:30-9:50|
|3-4|10:10-11:30|10:10-11:30|10:10-11:30|  |10:10-11:30|
|5-6|  |13:40-15:00|13:40-15:00|  |  |
|7-8|  |15:10-16:30|15:10-16:30|  |  |
|9-10|  |  | 18:00-19:20 |  |  |
### day1：网站环境搭建 - 4学时

1. PHPstudy([官网](https://m.xp.cn/))
2. thinkPHP([官网](http://www.thinkphp.cn/))
3. 配置本地站点和本地域名
4. 模板下载和使用（[Bootstrap](https://www.bootcss.com/)）
5. 初体验：helloworld
6. 学会看官方文档，使用搜索引擎([阿里巴巴矢量图标库](https://www.iconfont.cn/)、[Font Awesome](https://fontawesome.dashgame.com/)、[jQuery](https://jquery.com/))
7. （选修）Git 版本控制（[课程资源 Git Hub](https://github.com/zhangna111/2020-Maritime-Website-Training)）

### day2：前/后端知识点回顾 - 4学时

1. HTML：常用标签
2. CSS：栅格系统、常用样式、字体图标
3. jQuery：库引入、选择器、事件
4. MySQL：数据库操作
5. PHP：数据库连接、增删改查

### day3：前/后台页面设计 - 10学时

1. 首页：导航、banner、LOGO、商品列表、版权备案信息
2. 登录/注册页：用户名、密码、确认密码、验证码、表单校验、显示用户信息和退出登录
3. 商品列表：列表展示商品、分页
4. 商品详情：商品图文展示
5. 后台登录页：用户名、密码、验证码、管理员身份验证
6. 商品管理列表：列表展示商品、增删改按钮
7. 商品添加：添加商品信息表单
8. 商品修改：修改商品信息表单
9. (选做)用户管理：用户列表、用户增删改、设置管理员
10. (选做)商品分类：分类列表、分类增删改、为商品设置分类，前端按分类展示商品

### day4：数据库搭建、业务逻辑编写 - 8学时

1. 创建商城数据库 shopping_db
2. 用户表
3. 商品表
4. (选做)商品分类表
5. 登录/注册
6. 商品：展示、增删改
7. (选做)用户：用户列表、增删改
8. (选做)商品分类：分类列表、增删改、为商品设置分类


### day5：合成、测试、发布 - 4学时

1. 前端代码与后台逻辑整合
2. 本地浏览网站
3. 商品管理测试
4. 用户管理测试
5. 分类管理测试
6. 撰写实验报告
7. 打包站点

## 考察要求
### 1. 开发环境搭建
#### (1) 安装PHPstudy
#### (2) 安装Composer
在 Linux 和 Mac OS X 中可以运行如下命令：
```
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```
在 Windows 中，你需要下载并运行 Composer-Setup.exe。
#### (3) 使用Composer安装thinkphp 6.x
```
composer create-project topthink/think website_directory
```
#### (3) 修改.env文件，配置数据库，开启调试
#### (4) 配置站点、本地域名、开启虚拟服务器
```
php think run
```
### 2. 前端UI设计
引入BootStrap，讲将js和css文件夹拷贝至项目public/static下，配置config/view.php，设置静态调用的模板路径。
#### (1) 网站首页

* DIV+CSS栅格布局
* LOGO：用姓名拼音首字母设计个人商城LOGO
* 标题：为商城命名
* 关键字、描述和作者信息（学号+姓名）
* 导航：首页 index、商品列表 goods、管理入口 admin_学号、关于我们 about_us、登录/退出
* 多图可切换广告条（Banner）：设计至少4张产品宣传图，实现切换
* 商品列表：按规则（如：时间、goods_id、修改时间、推广标识等）展示部分商品，内容包括：商品图片、商品名称、规格、简介、价格等
* 底部信息：备案号、版权信息（学号+姓名）

#### (2) 用户注册/登录

* 注册表单：手机号（用户名）、密码、确认密码、昵称、备注。其中，用户名、密码、确认密码和昵称为必填项，校验手机号格式和密码格式（6位以上数字、字母组合），手机号唯一检测
* 注册成功：跳转首页并登录，导航条显示昵称和退出登录
* 注册失败：提示错误信息
* 登录：手机号、密码、验证码
* 登录成功：导航条显示昵称和退出登录
* 登录失败：提示错误信息
[表单验证插件](http://validform.club/)

#### (3) 商品列表

* 按照上架时间的先后，新上架的在前，展示商品列表
* 内容包括：商品图片、商品名称、规格、库存、简介、价格等
* 点击商品图片或名称，跳转商品详情页
* 分页

#### (4) 商品详情

* 展示对应的商品详情信息：商品编号、商品名称、图片、价格、规格、库存、图文描述等

#### (5) 关于我们

* 实验报告：表格排版、显示1像素边框

#### (6) 管理员登录

* 管理员账号、密码、验证码
* 登录成功：跳转商品管理列表
* 登录失败：提示错误信息

#### (7) 商品管理

* 分页列出所有商品，每个商品一行，显示必要的信息区别各个商品（如：编号、名称等），每行有编辑和删除按钮
* 添加商品按钮
* 添加商品表单
* 修改商品信息表单
* 点击删除按钮，弹出警告框，确认后再删除

#### (8) 用户管理(选做)

* 分页列出所有用户，每个用户一行，显示必要的信息区别各个商品，每行有编辑和删除按钮
* 添加用户按钮
* 添加用户表单
* 修改用户信息表单
* 点击删除按钮，弹出警告框，确认后再删除

#### (9) 商品分类管理(选做)

* 分页列出所有商品分类，每个分类一行，显示必要的信息区别各个商品，每行有编辑和删除按钮
* 添加商品按钮
* 添加商品表单
* 修改商品表单
* 点击删除按钮，弹出警告框，确认后再删除

### 3. 数据库

* 创建商城数据库 shopping_db
* 用户表 tb_users:user_id、用户名（手机号）、密码、昵称、备注、是否是管理员、注册时间、修改时间
* 商品表 tb_goods:goods_id、商品编号、商品名称、规格、库存、简介、价格等
* (选做)商品分类表 tb_goods-type:type_id、分类名称，相应的商品表需要添加type_id字段

### 4. 业务逻辑

#### (1) 登录/注册

* 登录：用户名（手机号）、密码查询，成功则跳转首页、失败则提示信息再返回首页
* 注册：新增用户记录，用户名（手机号）唯一，注册后执行登录操作

#### (2) 商品展示

* 首页：按规则读取指定个数商品，展示在首页上
* 商品列表：读取所有商品信息，分页展示
* 商品详情：读取指定商品信息，展示在详情页

#### (3) 商品管理：展示、增删改

* 商品列表：读取所有商品信息，分页展示
* 新增商品：添加商品记录，商品编号唯一
* 编辑商品：修改指定商品记录
* 删除商品：删除指定商品记录

#### (4) (选做)用户：用户列表、增删改

* 用户列表：读取所有用户信息，分页展示
* 新增用户：添加用户记录，用户名（手机号）唯一
* 编辑用户：修改指定商品记录
* 删除用户：删除指定商品记录，当前管理员不可删除

#### (5) (选做)商品分类：分类列表、增删改、为商品设置分类

* 商品分类列表：读取所有商品分类信息，分页展示
* 新增商品分类：添加商品分类记录，分类名称唯一
* 编辑商品分类：修改指定商品分类记录
* 删除商品分类：删除指定商品分类记录
* 新增商品和编辑商品时应有分类选择

[本课程示例](http://ecommerce.zrise.top/)
[课程Github](https://github.com/zoey-cheung/2020-Maritime-Website-Training)