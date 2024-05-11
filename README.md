# 资金费率套利系统

## 基础配置

### 账户注册

**币安邀请码**: 111042837

**币安邀请链接**:https://accounts.suitechsui.io/register?ref=111042837



### APP下载

**币安APP下载地址**:https://www.binance.com/en/download

**身份认证**  需要使用身份证认证

**账户安全设置** 谷歌验证器、邮箱验证



### 子账户

#### 子账户激活

需要激活子账户



#### 子账户创建

使用**普通邮箱**创建子账号。



#### 子账户开通合约

点击开通合约账户



#### 从母账户转入资金到子账户

从母账户转入需要投入的usdt到子账户的现货账户中



#### 子账户设置API

记录下 api_key、api_secret

设置受信任IP

**勾选允许的操作** 

​	允许读取

​    允许现货及杠杆交易

​    允许合约

   允许万向划转



## Q/A

### 多少资金可以跑策略？

10000U



### 资金安全方面的保障？ 

资金在你自己子账户的，子账号授权API没有提现功能。



### 利润的由来？

赚钱:通过合约做空，每天三次收取的资金费用。

亏钱:交易手续费,为了减少交易手续费，不能够频繁交易。

币价上涨:合约亏钱，现货赚钱，由于数量一致，金额对冲。

币价下跌:合约赚钱，现货亏钱，由于数量一致，金额对冲。



### 如何保证不爆仓?

设置合约6倍杠杆，倍数支持配置。

挑选上线时间大于30天的币种，天数支持配置，不做新币。

挑选资金费率前45的品种，数量支持配置，分散风险。

检查每个品种的持仓金额，大于规定的金额就会平仓。规定金额是动态计算的。

监控合约持仓的风险敞口率。不同敞口率配置不同的开仓和平仓条件。

风险利率越高，平仓条件越低，就会触发平仓。

现货和合约之间U的余额是动态划转的。保持可用余额接近。





### 怎么理解现货、合约、杠杆?

现货:买BTC，拥有BTC，可以提到钱包。

合约:对BTC（现货）价格上涨和下跌看法的分歧

做多:认为BTC价格马上要上涨,买入

做空:认为BTC价格马上要下跌,卖出

交易所:撮合做多和做空交易。

有做多，必然有对手做空，所以做空是意义的，牛市的时候，给以小博大的人，提供对手盘。

杠杆:收益和风险的放大器，杠杆能够放大你账户里面U的购买力，当你超额购买BTC的时候，放大了风险。
杠杆的倍数不是风险来源。

而是你开仓的数量价值的金额，和你合约账户的保证金余额之间的差额，这个才是真正的风险。





## 联系方式

### Telegram频道:

https://t.me/fund_rate_arbitrage



### 微信:

lyy_20131130

