<!-- omit in toc -->
# 宇浩输入法官方网站仓库

```txt
宇浩輸入法·傳統漢字简化汉字通打混輸·兼容大陸台灣字形標準·全漢字覆蓋·八萬詞庫·科學高效
```

>点击加入官方 QQ 群: [735728797](https://jq.qq.com/?_wv=1027&k=2OYDP4Tk) · 
>点击加入官方 Telegram 群: [yuhaoim](https://t.me/yuhaoim)  
>[简体字版官方网站](https://zhuyuhao.com/yuhao) · 
>[正(繁)體字版官方網站](https://zhuyuhao.com/yuhaoim)  
>[宇浩二代v2.0.0-rc下载(台湾字形支持)](https://github.com/forFudan/yuhao/releases/tag/v2.0.0-rc) · 
>[备用下载地址](https://gitee.com/forFudan/yuhao/releases/)  
>[快速入门](./docs/cookbook) · 
>[详细教程](./docs/learn) · 
>[在线练习](./docs/practice) · 
>[更新日志](./docs/updates/updates) · 
>[拆分查询(台湾字形支持)](./v2/chaifen/)  

「宇浩输入法」是一款字形输入法，由朱宇浩博士发明，具有以下特点：

- 重码率极低。一字一码，可以不看输入栏、不用选字、不用翻页，甚至闭上眼睛，流畅地进行写作。
- 繁简字分离，不存在共用码位现象，故而繁简混合文本也不需要选重。比如：「简」`QPJv`，「簡」`QKJv`。
- 繁體字形涵蓋大陸古籍、臺灣、香港、OpenCC 四套標準。比如：「起=走己」`DBjk` 和「起=走巳」`DCKk` 兼收。
- 设置简体、繁体两套词库。繁體詞庫涵蓋四套標準。繁體輸入體驗也極爲優秀。
- 面向大字集，全面覆盖 CJK 全字集 99000 多个汉字和部首（更新至 CJK 扩 I 区），可以用宇浩输入法打出所有生僻字。
- 字根在键盘上分横、竖、撇、捺、折五区排布，摒除乱序，便于上手。采用大字根，拆法更直观，不会将汉字拆得零碎。
- 双编码，不分主副根，没有结构码。全简一致，规则简单。取一、二、三、末字根，思维负担较轻。
- 拆字规则优先级明确，兼顾「逻辑性」和「直观性」。保证一字一拆、无歧义。
- 只使用25键，不使用Z键，手感好。中排、上排按键频率都超过40%。最高频的汉字一级简码位于最容易按的键上：`E的`、`F一`、`V了`、`I没`。
- 线性的学习体验，教程详尽。在简快码的加持下，只用记住100个字根，就能基本输入最常用的500个汉字，其他字根可以边打边学。

[RIME 三大方案](https://github.com/forFudan/yuhao/releases)：

- yuhao.schema.yaml 为简化汉字设置简码的方案，名为「开来学」。
- yuhao_tradition.schema.yaml 为传统汉字大陆字形设置简码的方案，名为「繼往聖」。
- yuhao_tradition_tw.schema.yaml 为传统汉字台湾字形设置简码的方案，名为「書同文」。

宇浩输入法的设计哲学是：**实用**、**直观**、**科学**、**理性**。实用，指的是完全以输入而非检字进行设计；直观，指的是对汉字的拆分直观易懂；科学，指的是对于编码和简码的设计科学合理，并符合统计频率；理性，指的是拆字规则逻辑严明、没有二义，也指社群抱着理性和开放的态度去面对批评和建议，积极修正存在矛盾的、不正确的拆分。
