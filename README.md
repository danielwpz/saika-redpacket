# saika

用于在Near链上发红包的合约
支持的代币：
* NEAR
* FungibleToken

支持的红包拆分模式：
* 平均拆分
* 随机拆分

支持的最大红包拆分数量：100

支持设置红包领取者白名单

将创建红包时传入的 public_key 绑定在创建者账户，对应的 private_key 公开给任何允许领取红包的用户，由创建者支付红包被领取产生的GAS费
