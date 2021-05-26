# 帶我了解Crucible

## 什麼是Crucible\(煉丹爐/坩堝\)？ 

它是一個代表你所提供LP的NFT。創建一個Crucible的行為被稱為 "鑄造"\(Minting\)。

當一個Crucible有LP提供到Aludel，持有者就會獲得⚗️和ETH。總獎勵是每14天發生的1%的通貨膨脹所創造的⚗️的50%，以及在最初的Balancer池中籌集的ETH。提供LP的Crucibles會獲得總獎勵的一部份，這是根據他們提供的LP占總LP的比例，以及他們的LP相對於其他LP的提供時期。

### 什麼是NFT？

它代表Non-Fungible Token\(非同質化代幣\)。如果這個詞彙對你來說太深奧，你可以把 "非同質化 "看作是 "獨特"的意思。

NFTs與代幣形成了直接的對比：

* 代幣：1⚗️就是1⚗️，它們的價值和用途是相等的。
* NFTs: 一個Crucible NFT不等同於另一個Crucible NFT，很少機會任何兩個Crucible的價值都是一樣的。 

明白這一點是非常重要的，因為人們已經開始[在Opensea等平台上列出他們的Crucible](https://opensea.io/assets/0x54e0395cfb4f39bef66dbcd5bd93cca4e9273d56/620479970925497750675476517677400441094103376596)進行銷售。

為了明確起見，值得一提的是: 如果你鑄造了一個Crucible，同時你也在Uniswap - V2的流動資金池中質押\(Stake\)了⚗️。你實際上有效地同時間運用了三種可能獲利的方式。

## 如何鑄造一個Crucible？

最初，唯一的方法是透過掌握官方的CLI工具。幸運的是，社群成員已經創建了網路應用程式，使這個過程變得更加容易。由於使用CLI工具時可能會有出錯的額外風險，因此不再建議採取這種方法。

請使用以下的指南來鑄造一個Crucible：

* [在crucible.alchemist.wtf鑄造Crucible](guides-crucible.alchemist.wtf/)

## 一個Crucible的價值是多少？

Crucible的NFT性質有可能使其具有超越其現有價值的投機價值，有些Crucible可能被認為比其他的更特殊。

撇開投機的因素，我們所知道的是，Crucibles是由不同數量的LP代幣所創造的，這些LP代幣的價值是可以立即衡量的。

至少，你可以根據取消提供其LP並兌換回法定貨幣來評估Crucible的價值。

有關檢查Crucible內容的方法，請參閱以下[這一節](teach-me-about-crucibles.md#how-can-i-check-how-many-lp-tokens-someone-elses-crucible-is-worth)。

## 你應該鑄造Crucible嗎?

這要由你來決定的。請確保你了解你能得到什麼，你能失去什麼，然後衡量這個選擇是否適合你。

#### 鑄造的成本

在處理基於Ethereum的代幣和合約時，幾乎在每個階段都會面臨gas費用。

Gas的價格持續波動，這是在預計要支付多少gas當中的重要因素，因此我們無法給出一個明確的指示。

然而，我們可以說的是，當你準備提交一筆交易來鑄造一個Crucible時，你應該考慮到你的LP代幣的價值相對於gas的成本。

#### 工具

我們的指南是基於我們建議的錢包，MetaMask ![](../.gitbook/assets/metamask-fox.svg)。如果你需要關於使用其他錢包的建議，請進入我們的[discord](http://discord.alchemist.wtf) 頻道，社群將很樂意回答這個問題。 

{% hint style="warning" %}
您必須[添加代幣地址](faq.md#why-cant-i-see-my-mist-in-my-wallet)，否則MetaMask不會自動識別或顯示您的Crucible代幣。 
{% endhint %}

## 我可以用什麼錢包來存儲我的Crucible？ 

Crucibles是ERC-721代幣，並不是所有錢包都支持這種交易簽名的。

 請參考我們的[錢包兼容性指南](wallet-compatibility.md)。

##  我需要多少LP代幣來創造一個Crucible？

社群成員曾經成功地用最低0.1LP的代幣鑄造了一個Crucible。 

當然，鑄造Crucible仍然需要gas費，所以在用少量的LP創造Crucible時，請考慮到這一項成本。

請記住，你賺取的獎勵是與你佔Adudel內裏的總LP份額成正比的。

## 我可以創建多個Crucible嗎？

可以的。社群中有許多用戶已經鑄造了多個Crucibles。

對於這是否有利的舉動，取決於您自己的看法。

## 我如何查看別人的Crucible值多少LP代幣？ 

你可以把Crucible的token ID，轉換為十六進制hexadecimal（如果本身是十進制decimal），然後在[etherscan.io](https://etherscan.io)上搜尋地址。

它將會顯示其內容以及Cricuble內的交易歷史。

如果您看不到有任何代幣，那麼它很可能是空的。

## 如何在MetaMask![](../.gitbook/assets/metamask-fox.svg)上查看我的代幣？ 

請參考我們的[常見問題FAQ ](faq.md#why-cant-i-see-my-mist-in-my-wallet)您需要在你的錢包添加什麼地址才能看到你的代幣。



