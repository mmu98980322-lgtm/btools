# 内盘封顶

{% hint style="success" %}
**B.Tools｜内盘封顶｜内盘剩余量低于设定时买入**

#### 用于还在内盘的曲线盘。剩余量降到阈值后买入封顶；可选毕业到外盘后再按比例卖出。

[**立即体验>>>**](https://b.tools/solana/curve-cap)
{% endhint %}

{% hint style="warning" %}
本页只认 Pump、Raydium Launchpad、Bonk 的内盘池，不支持 CLMM，也不能拿普通外盘池开始。
{% endhint %}

## 如何使用内盘封顶功能

1. 打开 [内盘封顶](https://b.tools/solana/curve-cap)。路由选对应发射台，查询代币，确认是内盘池。
2. 右侧导入并勾选参与封顶的钱包，查询余额。
3. 「目标」填写内盘剩余低于多少开始封顶，并选择封顶买入钱包组。
4. 需要毕业后卖掉时，打开「发射后外盘秒卖」，设置秒卖钱包组、秒卖比例和延迟秒数。
5. 链上区把封顶买入小费和发射卖出小费分开填写。
6. 点「开始内盘封顶」。剩余量还高于阈值时不下单。

{% hint style="warning" %}
未打开秒卖时，封顶买入完成后不会自动卖出。已经离开内盘、又还没完成封顶买入时，任务停在未封顶。毕业与否以链上状态为准。
{% endhint %}

### 图文教程

**1. 查到内盘池**

顶部选择链、发射台路由、主币和代币，点「查询池子」。页面提示需要 Pump 或 Launchpad 内盘池时，先换路由再查。

<figure><img src="../.gitbook/assets/image (211).png" alt=""><figcaption></figcaption></figure>

**2. 参与钱包**

勾选要拿来封顶买入的地址，并查过主币余额。秒卖用的是同一批里、秒卖钱包组对应的地址。

<figure><img src="../.gitbook/assets/image (212).png" alt=""><figcaption></figcaption></figure>

**3. 目标**

* 「内盘剩余低于多少开始封顶」：剩余量降到这个数及以下才买入。
* 封顶买入钱包组：这一侧实际下单的分组。不选则用右侧已勾选地址。

<figure><img src="../.gitbook/assets/image (213).png" alt=""><figcaption></figcaption></figure>

**4. 下单（发射后秒卖）**

打开后出现：

* 秒卖钱包组。
* 秒卖比例：相对这些钱包的持仓。常用 `100`，即卖掉持仓。
* 秒卖延迟（秒）：检测到毕业后再等这么久才卖。

接收方式可选留在卖出钱包，或归集到指定地址。归集时地址要核对清楚。

<figure><img src="../.gitbook/assets/image (214).png" alt=""><figcaption></figcaption></figure>

**5. 链上**

封顶买入小费、发射卖出小费分两栏。滑点、代付、同时笔数、自动合并、每钱包最低保留与其它策略相同。合并后多个钱包会进同一笔交易。

<figure><img src="../.gitbook/assets/image (215).png" alt=""><figcaption></figcaption></figure>

**6. 开始**

点「开始内盘封顶」。触发后页面会提示封顶买入已提交。开了秒卖时，检测到发射后再按比例卖出。点「停止」结束；若已经封顶，状态会显示已封顶。

已开通工作台时，这条任务会出现在工作台。刷新后需要在任务台重新启动。

***

**市值工具、钱包管理、转账工具——支持多条公链，私钥本地签名，打开即用**

**B.Tools —— 让 Web3 操作更简单。**

B.Tools社群

* 官网：[https://b.tools/](https://b.tools/solana/features)
* X/Twitter：[https://x.com/BdotTools](https://x.com/BdotTools)
* Telegram：[https://t.me/BTools\_Official](https://t.me/BTools_Official)

<mark style="color:$primary;">B.Tools</mark>_<mark style="color:$primary;">保留根据实际情况随时修改、调整或取消相关公告及服务内容的权利，恕不另行通知。以上信息仅供参考，不构成任何投资或交易建议。</mark>_<mark style="color:$primary;">B.Tools</mark>_<mark style="color:$primary;">不对平台相关虚拟资产、项目或产品作任何推荐或收益保证。虚拟资产价格波动较大，参与相关交易及链上活动存在较高风险，请充分了解相关风险并谨慎决策。</mark>_
