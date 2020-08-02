//获取所有的用户信息
http://localhost:3000/users

//获取id为1的用户信息
http://localhost:3000/users/1

//获取所有的公司信息
http://localhost:3000/companies

//获取单个的公司信息
http://localhost:3000/companies/1

//获取所有的公司id为3的用户信息
http://localhost:3000/companies/3/users

//根据公司名字获取
http://localhost:3000/companies?name=Micro

//根据公司名字获取多个
http://localhost:3000/companies?name=Micro&name=Apple

//获取一页只有两条数据
http://localhost:3000/companies?_page=1&_limit=2

//升序排序 asc升序 desc降序
http://localhost:3000/companies?_sort=name&_order=desc

//获取到年龄大于30的
http://localhost:3000/users?age_gte=30

//获取到年龄大于30小于40的
http://localhost:3000/users?age_gte=30&age_lte=40

//搜索用户信息
http://localhost:3000/users?q=h
