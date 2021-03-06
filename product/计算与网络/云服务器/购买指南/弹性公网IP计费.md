## 费用计算

### 公网网络费用

弹性公网 IP 产生的外网带宽流量将收取公网网络费用，详情请见 [定价中心](https://buy.cloud.tencent.com/price/idc)，计费规则参见 [购买公网网络](https://cloud.tencent.com/document/product/213/10578)。

### 资源占用费

>! 
> - 未绑定时长不足1小时则按比例计费，例如：闲置30分钟，则按小时单价 \* 0.5来计算，每小时结算1次。
> - 建议您主动并及时释放不再使用的弹性公网 IP ，以保证 IP 资源的合理利用，节省您的费用。操作指引参见 [释放弹性公网 IP](https://cloud.tencent.com/document/product/213/16586#.E9.87.8A.E6.94.BE.E5.BC.B9.E6.80.A7.E5.85.AC.E7.BD.91-ip)。

| 弹性公网 IP 状态 | 收费标准 |
|---------|---------|
| 绑定  | 不收取资源占用费 |
| 未绑定 | 收取资源占用费，[点此查看价格](https://buy.cloud.tencent.com/price/idc#.E5.BC.B9.E6.80.A7.E5.85.AC.E7.BD.91ip) |
| 释放 | 不再收取任何费用 |

## 欠费处理

### 账号欠费

- 账号欠费两小时内，弹性公网 IP 可正常使用且正常扣费。
- 若用户账户余额小于0元且持续超过2个小时，将会免费保留24小时。在账号余额大于0之前弹性公网 IP 保持不可操作状态。
- 若2+24小时后，账号余额仍为负，则账号下所有弹性公网 IP 将被释放。

### 绑定的云资源欠费

- 与弹性公网 IP 绑定的包年包月云服务器到期未进行续费，云服务器到期后弹性公网 IP 将进入弹性公网 IP 回收站并做网络隔离处理。
- 欠费7天该包年包月的云服务器仍未续费，则与之绑定的弹性公网 IP 做销毁处理。

