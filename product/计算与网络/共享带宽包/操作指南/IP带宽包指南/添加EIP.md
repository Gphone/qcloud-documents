>?目前共享带宽包处于内测阶段，如需使用，请提交 [内测申请](https://cloud.tencent.com/apply/p/8o8lmsr5nj8)。
>
创建共享带宽实例后，您需要将使用该共享带宽的 EIP 添加到共享带宽实例中。

## 限制说明
1. 仅支持按流量计费和按小时带宽计费的 EIP 加入共享带宽包，包年包月的 EIP 不支持加入共享带宽包。
2. 添加 EIP 到共享带宽包后，EIP 原本的计费模式将变更为共享带宽包模式，不额外收取流量费和带宽费用，但正常收取实例占有费。
3. EIP 的实例占有费与是否加入共享带宽包无关，当 EIP 绑定实例时，IP 的占有费用减免。
4. 单个共享带宽包最多可添加100个 EIP。

## 操作步骤
1. 登录 [私有网络控制台](https://console.cloud.tencent.com/vpc/vpc?rid=1)。
2. 单击左侧导航的【共享带宽包】。
3. 选择地域，在列表中找到目标共享带宽包实例，单击实例 ID 进入详情页。
4. 在详情页的“带宽包资源”模块，单击【+添加资源】。
5. 在弹窗中，选择资源类型和资源实例，单击【确定】即可。
![](https://main.qcloudimg.com/raw/b3aa545f5ecdd35f75cd4e4ac02da6bd.png)
