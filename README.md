### 分析过程

参考本人  [blog](https://blog.csdn.net/weixin_38737912/article/details/105253563)

### 爬取思路 (供参考)

    APP列表可以查1000条,单法院单天几乎没有超过这个限制 (想想之前APP列表只有20条的时候😓)
    
    就是构建查询条件, 按照时间+ 法院进行查询
    
    法院列表参考 resources目录下 court.json (2019爬取,3525个法院, 不保证现在也全)
    
    具体请求参数,可以再APP里修改后再抓包


### 更新日志

- 2020/04/17 测试 列表获取详情为空, App显示暂无数据

​                [文书网app 官方下载链接]( http://wenshu.court.gov.cn/MobilePage/mobile.html)    可自行测试

- 2020/04/20 测试正常使用
- 2020/04/23 测试正常使用, 新增爬取思路,法院json
- 2020/04/26 测试正常使用, 列表字段映射
- 2020/05/07 测试正常使用
- 2020/05/22 测试正常使用