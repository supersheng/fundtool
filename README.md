[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmaskleo%2Ffundtool.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmaskleo%2Ffundtool?ref=badge_shield)

### 基金分析

### 基金工具
- [x] 均线分析
- [ ] 当日偏离均线
- [ ] 最大回撤
- [ ] 夏普值
- [ ] 比较
- [ ] 定投回测计算


### 数据来源

- [历史收益](http://fund.eastmoney.com/f10/F10DataApi.aspx?type=lsjz&code='+fundCode+'&page=1&per=10000&sdate='+_sdate+'&edate='+_edate+'&rt=0.01230440990261572')
- [时时获取估值](http://fundgz.1234567.com.cn/js/020003.js?rt=1513263470578)
  ```javascript
    jsonpgz(
        {
        fundcode: "020003",
        name: "国泰金龙行业精选",
        jzrq: "2017-12-13",
        dwjz: "0.6560",
        gsz: "0.6520",
        gszzl: "-0.61",
        gztime: "2017-12-14 15:00"
        }
        )
  ```
  
  
  - https://www.zhihu.com/question/27264526
  
  - https://community.bigquant.com/t/%E9%87%8F%E5%8C%96%E5%AD%A6%E5%A0%82-%E7%AD%96%E7%95%A5%E5%BC%80%E5%8F%91%E7%AD%96%E7%95%A5%E5%9B%9E%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%8C%87%E6%A0%87%E8%AF%A6%E8%A7%A3/257
  
 - 平均年化投资回报率，它是一个年度化的平均月几何回报，未必与过去一年的实际年度回报相等，当然平均年化投资回报率越高就是越好的。
  
 - 阿尔法比率：他代表基金多大程度上超过了预期收益率，最好越大越好，说明超额收益可以获取的更多。
  
 - 标准差，是指基金每月的实际回报率相对平均回报率的偏差程度，标准差越大基金的波动就越大，也就是说波动越大，基金的稳定性就越差。
  
 - 夏普比率：它表示我们每承担一分风险，可以带来几分的回报，该比率越高，基金承担的单位风险得到的超额回报率就越高，该系数也是越高越好了！
  
 - 最大回撤：这个指标很多机构都要参考，就是基金控制风险的能力强不强，这个指标当然越小越好。基金单位净值小于3是因为，基金做了一段时间有收益了就把利润分配掉了，否则跌下来分红就没有了。


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmaskleo%2Ffundtool.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmaskleo%2Ffundtool?ref=badge_large)