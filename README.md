# iOSDev-Rules-Lucky-Bag-10
iOS 开发规范，操作错误的，请向对方立刻发放 **10 元红包**
```
本规范自 2016年7月20号 生效， 用于「医学时间」iOS 项目，由卓先生和米先生 CodeReview 新产生代码和函数时进行评估
```

###编码
- 除初始化布局的函数外，每个函数长度不超过50行
- 每个UIView的实例对象变量名都需要体现类型
```Swift
  let titleLabel = UILabel()
```
- Swift 文件内不允许撰写多余的 self
- service层的每个API都需要写注释
- 所写代码需没有警告，除非说明情况

###格式
- 两个函数之间需有一个换行
- 所有注释掉的代码函数或者空的函数都需要写说明否则删除
- 表示跳转到某个页面的方法以动词<code>go</code>开头
```Swift
     private func goNewsDetailViewController(){
        
    }
```

###项目
- 不允许提交 PodLock 文件至 Git
- 每次 Commit 需要说清楚所有功能，尽量分拆功能 Commit
- 当subview数量小于等于2时不使用xib
