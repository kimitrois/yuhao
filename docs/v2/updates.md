---
title: 测试日志
layout: default
parent: 测试区域
nav_order: 1
---

<!-- omit in toc -->
# 宇浩二代更新日誌

## 2023年6月12日

<del>宋天定製版</del>預覽版 v2.0.0-rc 發佈。最後的最後，它來了。

根據大量反饋（主要是宋大佬、麥大佬、笑大佬，還有群裏的小夥伴），作出以下調整。

删除字根：

- 歹 = 一夕 〔使用頻率較低〕
- 凡 = 几丶 〔使用頻率較低〕
- 攴 = 卜又 〔使用頻率較低〕
- 矛 = 予丿 〔使用頻率較低〕
- 爾 = 一八巾乂乂乂乂 〔使用頻率太低〕
- 羽 = 习习 〔對立較少，没有必要分離〕

增加字根：

- 里 Kk 〔避免因筆順造成的歧義，呼聲很高。同時，改善了高頻「重」、「動」等字的手感。且「重」字不再需要使用繁體字根「車」。〕
- 高（亠口、亠口冖）Ol 連續編碼 〔這個是初版的字根，現恢復它，目的是離散「京」「亮」等字。注意，存在歪脖拆的可能：襄 = {亠口}口𠀎𧘇。還要注意穿插：衷：{亠口}丨𧘇〕
- {⺍一} Is 爲「氵」的附屬根 〔這是爲了和丷䒑一致。所以：兴 = {⺍一}八，应 = 广{⺍一}〕
- 彑 Bm 同{互中}。〔「彐」和「彑」其實是同字不同形。「彑」爲字根很，「緑」「綠」等字同構同拆。且「互」和「亞」「亚」拆法相同。〕

改變小碼：

- 氵 Ic -> Is 〔取其聲母〕
- 习 Xu -> Xi 〔取其韻母，正好等於該字全拼〕

豎不包夾：

- 豎向離散的字根，不可包夾其他字根。特别的，「二」「三」出現包夾，就拆爲分散的「一」，如：亘 = 一日一，畺 = 一田一田一。減少判斷的難度。

部分臺灣字形拆分補充和修正：

- 沉 = 氵冖儿
- 麥 = 來夊〔上方視作「來」的變形，拆爲「十人人人」没有必要。〕

簡體前150字，編碼改變五個：

- 重 = 千里
- 高 = 高
- 就 = {京頭}小尤
- 没 IQhc -> IQhs
- 应= 广{兴頭}

優化繁體簡碼的設置，縮減碼長。

以下爲重碼數據對比：

| 形碼方案        | GB2312 | 通規一二級 | 國字常用 | 常用繁簡 |  GBK | 簡體選重率 | 繁體選重率 | 繁簡混合文本選重率 | 簡體詞語选重率 |
| :-------------- | -----: | ---------: | -------: | -------: | ---: | :--------- | :--------- | :----------------- | :------------- |
| 宇浩v2.0.0-rc |    314 |        265 |      208 |      583 | 5171 | 5.2‱       | 15.3‱      | 17.1‱              | 116.1‱         |
| 宇浩v2.0.0-rc   |    318 |        273 |      202 |      584 | 5178 | 4.9‱       | 15.1‱      | 16.6‱              | 109.7‱         |

以下是對於部分意見的反饋：

某位不願透露姓名的宋姓大佬：能不能二三不包夾？不然總是轉不過彎來。  
反饋：可以的，不過靜態重碼會上升。  
某位不願透露姓名的宋姓大佬：最好豎向的組合字根都不包夾。  
反饋：可以可以，大佬肯背書就好。

某位不願透露姓名的宋姓大佬：彑和{互中}合併。
反饋：好的。

小夥伴：「重」居然要用繁體根「車」。而且「里」的筆順總是弄錯。
反饋：「里」值得一個字根。重 = 千里，手感提升。

小夥伴：舞 = 𠂉卌歹ヰ？真丑。
反饋：「歹」删了！

小夥伴：「凡」「攴」爲什麼是字根？
反饋：同意，這倆頻率太低，删了。

小夥伴：羽 = 习习？
反饋：「习」除了「𠁨」外沒有單獨使用的，所以把它作爲了「羽」的附屬。不過旣然不存在對立，把「羽」删了也好。

小夥伴：「亠口」可以分離「京」「高」等字形，否則打詞不舒服。
反饋：同意，恢復高字根，「亠口」「亠口冖」作爲它的附屬，小碼就用「口」的區碼 L。

小夥伴：碼長有些長。
反饋：同意，簡碼過於陳舊，有的一、二簡還是重複的，需要更新一下。

## 2023年6月11日

恢復簡體簡碼中的两個一簡字：

- C 好
- O 为

「二」「三」包夾不再分情况討論，一律允許包夾，包括：

亜唖悪戩晉𠀥𡏍𢳩𣊰𣱌𤇟𤉁𤐦𤩖𨫌𪬕𪰥𫠱𫫖𫰫𬂲𬅂𰤐

## 2023年6月10日

優化簡體簡碼設置，縮減碼長。

特别的，一簡有以下變化：

- C 好 0.38% -> 也 0.50%
- H 地 0.46% -> 到 0.61%
- O 为 0.39% -> 说 0.63%
- T 个 0.78% -> 人 0.97%

二簡有以下變化：

- CV 始 -> 好
- HC 车 -> 地
- OX 辛 -> 为
- TN 用 -> 个

調整結果如下：

| 方案        | 毛泽东选集(简) | 天龙八部(简) | 三体(简) | 战争与和平(简) | 史記(繁) | 紅樓夢(繁) | 笑傲江湖(繁) | 論語集解(繁簡混) |
| :---------- | -------------: | -----------: | -------: | -------------: | -------: | ---------: | -----------: | ---------------: |
| 五笔86      |           3.12 |         3.31 |     3.21 |           3.24 |     3.59 |       3.44 |         3.45 |             3.49 |
| 五笔98      |           3.05 |         3.19 |     3.12 |           3.15 |     3.42 |       3.32 |         3.32 |             3.29 |
| 蓝宝石      |           3.04 |          3.1 |     3.03 |           3.05 |     3.48 |       3.29 |         3.29 |             3.36 |
| 徐码23      |           3.15 |         3.21 |     3.18 |           3.17 |     3.49 |       3.32 |         3.33 |             3.33 |
| 宇浩·調整前 |           3.16 |         3.16 |     3.09 |           3.11 |     3.51 |       3.29 |         3.32 |             3.41 |
| 宇浩·調整后 |           3.13 |         3.12 |     3.06 |           3.09 |     3.52 |       3.28 |          3.3 |             3.38 |

## 2023年6月9日

「卿」由「𠂎彐厶卩」改拆「卯彐厶」，因爲少根。

此更改還影響大字集中相似字形漢字4個：𣛬𦺄𬁋𮬐

## 2023年6月1日

本次更改後爲公測版，非必要不再更改字根。

小碼改變：

- 二 Se -> Si 分散雙手
- 宀 Oo -> Ob 聲母「寶蓋」
- 立 Ii -> Id 分散雙手
- 业 Kk -> Kg 分散雙手
- 早 Jo -> Jd 連續小碼「日十」分散雙手
- 彐 Xx -> Xl 分散雙手
- 阝 Cf -> Cj 分散雙手

## 2023年5月31日

小碼改變：

- 业 Kk -> Ki

## 2023年5月30日

字根認定：

- 認定「业」爲字根，編碼爲 Kk

受其影響，簡體優先方案的簡碼位有如下變化：

- uk 赢 -> 普
- un 普 -> 烟
- kk 婴 -> 业
- nu 业 -> 圈
- jk 映 -> 显
- jn 显 -> 崮
- mk 帽 -> 虚
- mn 虚 -> 皿

受其影響，繁體優先方案的二簡位有如下變化：

- n 對 -> 回
- ku 剛 -> 對
- nl 回 -> 圖
- un 普 -> 廠
- mn 虚 -> 皿

## 2023年5月29日

小碼改變：

- 龰 Nd -> Nf 避讓「鬥」

## 2023年5月28日

字根認定：

- 認定「𦣞」「𦣝」字根同「臣」，如 熙 = 臣巳灬，姫 = 姬 = 姬 = 女臣
- 認定「𦍌」字根同「羊」，如 美 = 羊大，義 = 羊我 = 羊丿扌戈

小碼改變：

- 身 We -> Wm 分散雙手

## 2023年5月25日

小碼改變：

- 飛 Bf -> Bk 分散雙手
- 龰 Nh -> Nn -> Nd 防止 Nh 單指跨行
- 彡 Ti -> To 讓出碼位給「八」
- 八 Tb -> Td -> Ti 防止 Tb 單指大跨行，分散雙手
- 乃 Va -> Vj 分散雙手
- 九 Yj -> Yf 分散雙手，汉字密度 Yj19 Yf11

## 2023年5月23日

增加一個文件夾 [generator](../../beta/generator/)，包含三個用來生成一級、二級、三級簡碼字詞的文件。如果發現任何 bug，可以直接提出 issue 或者 push commits。

## 2023年5月22日

四重註解中，詞語編碼用大小寫來區分大小碼。

加入「功能開關一鍵配置」文件：

- yuhao.custom.yaml
- yuhao_tradition.custom.yaml
- yuhao_tradition_tw.custom.yaml

删除「四豎」字根，因爲只在全字集中被使用了一次。

## 2023年5月21日

RIME 增加拼音註解。現總共爲四重註解。

小碼改變：

- 凵 Xa -> Xe -> Xg 韻母「丱」，防止大跨行

## 2023年5月20日

增加測試版方案的[在線字根練習](../../beta/practice/practice.html)。

小碼改變：

- 其 Dq -> Dj 聲母，減少小拇指負擔
- 凵 Xa -> Xe 韻母

## 2023年5月19日

增加近四千個臺灣字形兼容拆分，調整臺灣方案簡碼。凡臺灣繁體詞語，都使用臺灣字形編碼。比如「起來=走己來」`DBDl` 和「起=走巳來」`DCDl` 兼收。

在線拆分系統現也增加臺灣拆分一欄。

小碼改變：

- 氵 Iv -> Iu -> Ic 分散雙手
- 艹 So -> Sa -> Sj 韻母，防止 Sa 無名指小拇指連擊
- 乂 Wa -> Wl 分散雙手

## 2023年5月18日

小碼改變：

- 扌 As -> Ao 韻母，防止 As 無名指小拇指連擊
- 壬 Er -> En 韻母，分散雙手，汉字密度 Er22 En14
- 士 Hh -> Hf 分散雙手
- 户 Ih -> Ie 分散雙手
- 水 Kh -> Kv 韻母 u 轉 v，汉字密度 Kv7 Kh13
- 冂 Kg -> Kf， 同 「匚」Gf小碼一致
- 目 Mu -> Mk -> Mf，增加双手互击。
- 虎 Mh -> Mu 韻母，汉字密度 Mh20 Mu6
- 巾 Mv -> Mj -> Mv
- 王 Gv -> Gw -> Gn，增加双手互击，汉字密度 Gw25 Gn7
- 龰 Nh -> Nn， 防止 Mh 單指跨行，汉字密度 Nh 13 Nn 5
- 之 Pc -> Pe，改善手感
- 𠂇 Sv -> Ss -> So 「左」韻母。
- 巛 Vh -> Vc，聲母，同 「川」Qc 小碼一致，汉字密度 Vc3 Vh11

增加一個自定義碼表：yuhao.private.dict.yaml，優先級高於官方詞庫。原自定義碼表 yuhao.private.dict.yaml 優先級低於官方詞庫。
