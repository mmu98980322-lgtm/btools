# 低吸高抛

{% hint style="success" %}
**B.Tools｜低吸高抛｜跌到线买入，涨到线卖出**

#### 监控当前价格。跌到低吸触发价时买入，涨到高抛触发价时卖出。低吸价必须低于高抛价。

[**立即体验>>>**](https://b.tools/solana/buy-low-sell-high)
{% endhint %}

## 如何使用低吸高抛功能

1. 打开 [低吸高抛](https://b.tools/solana/buy-low-sell-high)，查询代币和池子。
2. 在右侧「参与钱包」导入地址或从钱包助手选择，勾选要参与的行，再查询余额。买卖用的是这一批勾选地址。
3. 左侧「目标」选择按单价还是按市值，填写低吸触发价和高抛触发价。
4. 「下单」里分别设置买入和卖出：钱包组、每一笔的数量或比例、间隔。
5. 「上限」为买卖各一套。填 `0` 或留空表示该项不限，谁先到谁停。
6. 链上区设置小费和滑点，一般保持默认。
7. 点「开始低吸高抛」。现价没到线时只盯价格，不会下单。停止时点「停止」。

{% hint style="warning" %}
已开通工作台时，点开始后任务会出现在工作台任务台。刷新页面后任务会停，需要在任务台重新点「启动」。未开通工作台时，任务只在本页跑，离开页面后不会在后台继续。
{% endhint %}

### 图文教程

**1. 打开页面并查池**

页面是左参数、右参与钱包。顶部一行：链、路由、主币、代币、「查询池子」。

<figure><img src="../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

**2. 勾选参与钱包**

* 钱包助手或「导入地址」。勾选「追加」会在现有列表上加地址；不勾选则替换当前列表。
* 勾选行后再查询余额。未勾选的地址不参与。
* 「低吸钱包组」「高抛钱包组」只决定这一侧看哪一组，买卖仍来自右侧已勾选的地址。

<figure><img src="../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>

**3. 目标**

* 目标类型：单价或市值。
* 低吸触发价：现价跌到这里及以下时买入。
* 高抛触发价：现价涨到这里及以上时卖出。
* 低吸触发价必须小于高抛触发价，否则不能开始。

<figure><img src="../.gitbook/assets/image (208).png" alt=""><figcaption></figcaption></figure>

**4. 下单**

买入（绿色）和卖出（红色）各一块：

* 买入：按数量，或按余额比例；固定金额，或最小到最大的随机区间。间隔为固定秒数，或最小到最大的随机秒数。
* 卖出：按持仓比例，或按持仓数量；同样可选固定或随机，并单独设置卖出间隔。

<figure><img src="../.gitbook/assets/image (209).png" alt=""><figcaption></figcaption></figure>

**5. 上限和链上**

上限默认展开，买卖各有：单地址累计、单地址次数、单笔上限、累计最大、总次数、运行时长（分钟）。旁边的已累计、已运行只读。

链上：小费可点「正常 / 快速 / 极速」或手填；滑点；代付；同时笔数；自动合并；每钱包最低保留。

<figure><img src="../.gitbook/assets/image (210).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
自动合并后，多个钱包会出现在同一笔交易里，容易被看成同一主体。
{% endhint %}

**6. 开始后看进度**

按钮下方会显示本轮大约买了多少。到上限、时长，或点「停止」后结束。日志在页面的日志里看。

***

**市值工具、钱包管理、转账工具——支持多条公链，私钥本地签名，打开即用**

**B.Tools —— 让 Web3 操作更简单。**

B.Tools社群

* 官网：[https://b.tools/](https://b.tools/solana/features)
* X/Twitter：[https://x.com/BdotTools](https://x.com/BdotTools)
* Telegram：[https://t.me/BTools\_Official](https://t.me/BTools_Official)

<mark style="color:$primary;">B.Tools</mark>_<mark style="color:$primary;">保留根据实际情况随时修改、调整或取消相关公告及服务内容的权利，恕不另行通知。以上信息仅供参考，不构成任何投资或交易建议。</mark>_<mark style="color:$primary;">B.Tools</mark>_<mark style="color:$primary;">不对平台相关虚拟资产、项目或产品作任何推荐或收益保证。虚拟资产价格波动较大，参与相关交易及链上活动存在较高风险，请充分了解相关风险并谨慎决策。</mark>_
