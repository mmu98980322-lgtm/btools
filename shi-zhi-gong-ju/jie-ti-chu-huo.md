# 阶梯出货

{% hint style="success" %}
**B.Tools｜阶梯出货｜到档后按该档买入或卖出**

#### 市值台阶出货，市值或价格到达某一档，就用该档钱包组买或卖。未到档位不下单。

[**立即体验>>>**](https://b.tools/solana/mcap-ladder-exit)
{% endhint %}

## 如何使用市值台阶功能

1. 打开 [阶梯出货（市值台阶）](https://b.tools/solana/mcap-ladder-exit)，查询代币和池子。
2. 右侧导入地址并查询余额。每一档可以指定自己的钱包组。
3. 「目标」先选按市值还是按单价，再添加档位。
4. 每一档填写触发值、方向（买入或卖出）、钱包组、下单方式，以及固定或随机的数量。
5. 可选填写停止卖出价。价格落到该值及以下时，停止并结束。
6. 「下单」设置档与档之间的巡检间隔。
7. 点「开始台阶出货」。全部档位触发后自动结束。

### 图文教程

**1. 查池和钱包**

与市值交易一样先查池。右侧勾选的地址，是各档钱包组可以选到的范围。卖出档要先查到代币余额。

<figure><img src="../.gitbook/assets/image (220).png" alt=""><figcaption></figcaption></figure>

**2. 每一档填什么**

点添加档位。一档一块，买入为绿色，卖出为红色。

* 台阶 N 钱包组：这一档用哪些分组。不选表示用当前可见的已勾选地址。
* 触发值：按上面的目标类型，填市值或单价。现价或现市值达到这一档才执行。
* 方向：买入或卖出。换方向后，这一档的数量要按新方向再看一眼。
* 下单方式：
  * 买入：按数量，或按余额比例。
  * 卖出：按持仓比例，或按数量。
* 固定或随机。随机时填这一档的最小和最大。卖出按比例时，`100` 表示该档钱包各自全部卖出。

不需要的档可以删除。

<figure><img src="../.gitbook/assets/image (221).png" alt=""><figcaption></figcaption></figure>

**3. 停止卖出价和间隔**

停止卖出价可选。现价小于等于它时，不再执行后面的档。

档间间隔是看下一档之前等待的秒数，可以固定，也可以随机一个区间。

<figure><img src="../.gitbook/assets/image (222).png" alt=""><figcaption></figcaption></figure>

**4. 链上和开始**

小费、滑点、代付、同时笔数、自动合并、最低保留在链上区。合并后同一档的多个钱包可能出现在同一笔交易里。

开始后，页面显示已触发多少档。点「停止」立刻结束。已开通工作台时，任务在工作台里看；刷新后需要重新启动。

***

**市值工具、钱包管理、转账工具——支持多条公链，私钥本地签名，打开即用**

**B.Tools —— 让 Web3 操作更简单。**

B.Tools社群

* 官网：[https://b.tools/](https://b.tools/solana/features)
* X/Twitter：[https://x.com/BdotTools](https://x.com/BdotTools)
* Telegram：[https://t.me/BTools\_Official](https://t.me/BTools_Official)

<mark style="color:$primary;">B.Tools</mark>_<mark style="color:$primary;">保留根据实际情况随时修改、调整或取消相关公告及服务内容的权利，恕不另行通知。以上信息仅供参考，不构成任何投资或交易建议。</mark>_<mark style="color:$primary;">B.Tools</mark>_<mark style="color:$primary;">不对平台相关虚拟资产、项目或产品作任何推荐或收益保证。虚拟资产价格波动较大，参与相关交易及链上活动存在较高风险，请充分了解相关风险并谨慎决策。</mark>_
