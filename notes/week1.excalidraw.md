---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Machine Learning ^V98MtTA7

supervised learning 
监督学习 ^dLE3qzpK

regression
回归 ^2jxO2BT9

classification
分类 ^R2FXwGlk

Predict a number
infinitely many possible outputs

已知大量房价信息
input: 房子信息
output: 房子价格 (价格的可能性是无限的)
 ^B0DXYnz5

Predict categories
small number of possible outpus

已知大量肿瘤信息及其是良性还是恶性的数据
input: 肿瘤信息
output: 肿瘤是良性还是恶行 (两个结果选其一) ^VXQ2ORUv

Learn from data labeled
with the "right answers" ^aL7a3S2Z

unsupervised learning 
无监督学习 ^FyMqHPYU

Find something interesting
in unlabeled data

has to find structure in the data ^ObcZHlEV

clustering
聚类 ^5TS7ggQw

Anomaly detection
异常检查 ^Bpt7t9kU

Group similar data points together.

将具有相同关键字的新闻聚到一起, 类似Google News
input: 各种新闻文章
output: 将相同特性的文章聚在一起. ^X3SP5xPy

Find unusual data points ^75pAKB5C

Dimensionality reduction
降维 ^2mFctrNh

Compress data using fewer numbers ^rBJjOVns

# The Terminology
training set, feature, target, m=number of training examples, (x, y) = single training example ^LqRXJMJO

# Linear regression

回归模型属于监督学习, 提供正确的feature和target大量数据, 让model拟合出一条linear regression.  ^WwMoVUVy

Regression model, predicts numbers, infinitely many possible outputs.
Classification model, predicts categories, small number of possible outputs. ^hwbVWO9k

# Mindmap for machine learning ^mW8uERUI

# Cost Function ^u0pu0q5h

Cost, 一个线性回归模型, linear方程, 预测targets和实际的targets之间的平方差.

为什么要计算Cost?
为了拟合一条cost最小的linear regression. cost越小, 越接近真实的targets.

 ^NUGCTc8u

w, b 被称为Parameter ^gtjX9QWv

如何计算并得到最小Cost的linear regression model?
首先, 我们简化, 只有一个w, b=0.
当只有一个parameter, w时, J(w)的Cost函数, 其实就是斜率函数 ^0CkyQn0K

接下来, 我们将b添加回来, 这样就会有两个parameter, 同样J(w)的cost可视化如下. ^m86LMwqL

# Gradient Descent ^iRYKytWy

梯度下降

比喻一下, 就是一个人在凹凸不平的山林, 从高点走到最低点.
1. 从一个点开始, 每次360度看一圈, 找一个坡度下降最大的点, 向下走.
2. 不断重复步骤1, 直到到达最低点.
3. 从另一个点开始, 重复1,2步骤, 达到最低点.

如图的两条路径, 最终到达的都是local minima, 局部最低点.

其次, 梯度下降的特性, 就是分别从两个出发点到达的最低点是相互不知的. ^cZWstGyR

learning rate, 控制下降步子的大小, 调整参数, 步长.
derivative term, 导数项(来自微积分)(偏导), 朝哪个方向迈出婴儿步, 方向.
partial derivative, 偏导数

repeat util convergence, 重复到收敛

w, b需要同步更新, 而不是更新好w立刻作为更新b的输入.
 ^F2q0HB3N

如果我们把导数部分提取出来, 从其结果的正负如何影响到w和b, 就能理解梯度下降. ^dUbkEhbc

why -2?
右边的点减去左边的点.
导数主要是通过dw/dJ(w)计算得到的. ^CSlMJxyv

## Derivative ^HvJSKflL

## Learning rate ^FawvxES3

学习率, 控制步长. 
过大, 导致无法到达最低点.
过小, 梯度下降速度慢. ^he6JacwB

linear regression model ^gqVSM8mb

获取最适合的
线性回归模型

最适合 -> 预测误差最小 ^grNoZ0fO

获取最小成本
均方误差(MSE)

计算, w, b ^7f7U5gAg

Cost function ^0MebN1T3

Gradient descent ^JMBNnIa6

梯度下降算法
计算最小成本
同时更新, wb
直到w和b停止更新 ^DH52eNQ0

Derivative ^1e9c8ZB9

导数 ^RPBy7xOb

Learning Rate ^UdnmFRTQ

学习率 ^CiKLrdKJ

为了预测误差最小
计算适合的w和b ^mCd6YIsw

获取局部最小 ^O6Qsmhzu

可视化 ^ij9sq61b

为什么要使用梯度下降?

仔细看右边的图, 
Linear regression是一个典型的凸函数, 全局只有一个最低点. ^NCdZsQqy

凸函数, Convex function. ^ri2PVrnZ

因为是凸函数, 所以学习率固定, 偏导数会随着斜率趋于0, 
最终, 也能到达最低点. ^CQWGamPd

斜率 ^ifuaFQJO

步长 ^tTtno8Ht


# Embedded files
459241ea8e1099fc927ef98a2b17754fe1ead925: [[resources/Pasted Image 20231125195833_134.png]]
f195d58f23ad3daabbf4ca59dd40f2b2f7a93f52: [[resources/Pasted Image 20231125201803_334.png]]
8337d91000e7188fa033f0b45cb121abaa361a0f: [[resources/Pasted Image 20231125203817_437.png]]
85947bf193769b617848e7e73862f0e26eb4993f: [[resources/Pasted Image 20231125204150_522.png]]
adc7bf209aeb9887831b5a19e30b56ade31ebd6b: [[resources/Pasted Image 20231125205955_683.png]]
12650067943434d41549f17e2f0184a32249b9ef: [[resources/Pasted Image 20231125214537_434.png]]
465fdf1a18bfd9e1271ec8e06b01603435f6124d: [[resources/Pasted Image 20231125220358_591.png]]
8ac4ed5bd704af915d55c1675b727ac02e4019b9: [[resources/Pasted Image 20231125221051_685.png]]
7cdf04f5d38c4fb6eabcab34502fb6882d0e47e2: [[resources/Pasted Image 20231126225427_403.png]]
f2fcb088d2b5770eb474aa03213f3df2be037ee2: [[resources/Pasted Image 20231202142122_552.png]]
be38fa6e70dfe4040fa25af4b10dea84d6a33383: [[resources/Pasted Image 20231202142138_588.png]]
d36759399429b17971c894122d88910bbfeb66d1: [[resources/Pasted Image 20231202143431_361.png]]
3e46a8289c0beef4b7743fb67296db0fc0f402ca: [[resources/Pasted Image 20231202144605_946.png]]
f18200570d2c24aeccde046e2775efc0dba9c54f: [[resources/Pasted Image 20231202144725_971.png]]
2008f6569c530f6be24d92dc8aa5fdf89006403a: [[resources/Pasted Image 20231202145211_096.png]]
233023fdf05efd38b016a66dd94eda3139d13e14: [[resources/Pasted Image 20231202145239_273.png]]
6f88a8d19f4faadb1dc86ce467d10999b4abe029: [[resources/Pasted Image 20231202152250_830.png]]
d765776dc384508428e3fda18bbc739b5180d098: [[resources/Pasted Image 20231202154948_311.png]]
a567db0057c371f3a83abd140f7e93d847942469: [[resources/Pasted Image 20231202155048_323.png]]
b011aa504cd9ba7dfda05fc75ed0753ae359764c: [[resources/Pasted Image 20231202160103_366.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.3",
	"elements": [
		{
			"type": "rectangle",
			"version": 679,
			"versionNonce": 603995376,
			"isDeleted": false,
			"id": "RCtE_NuJ-3fCUi0ViQC96",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -349.2620303535998,
			"y": -210.091195250532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 188.66668701171875,
			"height": 54.666656494140625,
			"seed": 1132789301,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "V98MtTA7"
				},
				{
					"id": "IvWsf1nJ5GO4onCOp4yBn",
					"type": "arrow"
				},
				{
					"id": "u_CfVIZ9DPqfP4w1YyReM",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 962,
			"versionNonce": 1222789648,
			"isDeleted": false,
			"id": "V98MtTA7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -335.51862977986934,
			"y": -195.25786700346168,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.1798858642578,
			"height": 25,
			"seed": 1687475157,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Machine Learning",
			"rawText": "Machine Learning",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "RCtE_NuJ-3fCUi0ViQC96",
			"originalText": "Machine Learning",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 856,
			"versionNonce": 1691033328,
			"isDeleted": false,
			"id": "iI0EUlEuFOB1EEspp-R5M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260.52055467744356,
			"y": -487.8499019672637,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 62.384069927604074,
			"seed": 1609473179,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "2jxO2BT9",
					"type": "text"
				},
				{
					"id": "FBwUP0Lf1hh3VU2K3LgDV",
					"type": "arrow"
				},
				{
					"id": "8tRqsb0R10cKeAZK5pQK_",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 712,
			"versionNonce": 2016315408,
			"isDeleted": false,
			"id": "2jxO2BT9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 333.26855953427383,
			"y": -481.65786700346166,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.61988830566406,
			"height": 50,
			"seed": 918966587,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "regression\n回归",
			"rawText": "regression\n回归",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "iI0EUlEuFOB1EEspp-R5M",
			"originalText": "regression\n回归",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 1233,
			"versionNonce": 526726896,
			"isDeleted": false,
			"id": "IvWsf1nJ5GO4onCOp4yBn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.53980028257598,
			"y": -211.09119525053202,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 160.94445694069492,
			"height": 142.58600738583598,
			"seed": 1766007419,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063437,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "RCtE_NuJ-3fCUi0ViQC96",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "fKij4jTMEcxLa_lhhahXr",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					111.94445694069492,
					-141.66667175292966
				],
				[
					160.94445694069492,
					-142.58600738583598
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1005,
			"versionNonce": 792921616,
			"isDeleted": false,
			"id": "tIXqoYt7pIyyf6cif5KJS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260.52055467744356,
			"y": -298.9499019672637,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 62.384069927604074,
			"seed": 1693020859,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "R2FXwGlk",
					"type": "text"
				},
				{
					"id": "QjReOLRGhKsCQEPZ2f5cq",
					"type": "arrow"
				},
				{
					"id": "z1gryULx8-yDPQZIZfcXC",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 892,
			"versionNonce": 518267632,
			"isDeleted": false,
			"id": "R2FXwGlk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 316.91856868954727,
			"y": -292.7578670034617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.3198699951172,
			"height": 50,
			"seed": 507601755,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "classification\n分类",
			"rawText": "classification\n分类",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "tIXqoYt7pIyyf6cif5KJS",
			"originalText": "classification\n分类",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 645,
			"versionNonce": 1568725232,
			"isDeleted": false,
			"id": "FBwUP0Lf1hh3VU2K3LgDV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 102.97478113686222,
			"y": -388.1499019672637,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 156.54577354058134,
			"height": 66.2273006691043,
			"seed": 2016169211,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063437,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "fKij4jTMEcxLa_lhhahXr",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "iI0EUlEuFOB1EEspp-R5M",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					107.54577354058134,
					-65.30796503619797
				],
				[
					156.54577354058134,
					-66.2273006691043
				]
			]
		},
		{
			"type": "arrow",
			"version": 685,
			"versionNonce": 1540897520,
			"isDeleted": false,
			"id": "QjReOLRGhKsCQEPZ2f5cq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 110.77068929408,
			"y": -323.76583203965964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 148.74986538336356,
			"height": 53.72730066910424,
			"seed": 1646607093,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063437,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "fKij4jTMEcxLa_lhhahXr",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "tIXqoYt7pIyyf6cif5KJS",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					99.74986538336356,
					52.80796503619797
				],
				[
					148.74986538336356,
					53.72730066910424
				]
			]
		},
		{
			"type": "text",
			"version": 788,
			"versionNonce": 1235534352,
			"isDeleted": false,
			"id": "B0DXYnz5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 591.6364526967682,
			"y": -544.1578670034617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 386.159912109375,
			"height": 175,
			"seed": 2020671675,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "8tRqsb0R10cKeAZK5pQK_",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Predict a number\ninfinitely many possible outputs\n\n已知大量房价信息\ninput: 房子信息\noutput: 房子价格 (价格的可能性是无限的)\n",
			"rawText": "Predict a number\ninfinitely many possible outputs\n\n已知大量房价信息\ninput: 房子信息\noutput: 房子价格 (价格的可能性是无限的)\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Predict a number\ninfinitely many possible outputs\n\n已知大量房价信息\ninput: 房子信息\noutput: 房子价格 (价格的可能性是无限的)\n",
			"lineHeight": 1.25,
			"baseline": 168
		},
		{
			"type": "text",
			"version": 702,
			"versionNonce": 562833136,
			"isDeleted": false,
			"id": "VXQ2ORUv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 591.6364526967682,
			"y": -342.7578670034617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 426.159912109375,
			"height": 150,
			"seed": 132337653,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "z1gryULx8-yDPQZIZfcXC",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Predict categories\nsmall number of possible outpus\n\n已知大量肿瘤信息及其是良性还是恶性的数据\ninput: 肿瘤信息\noutput: 肿瘤是良性还是恶行 (两个结果选其一)",
			"rawText": "Predict categories\nsmall number of possible outpus\n\n已知大量肿瘤信息及其是良性还是恶性的数据\ninput: 肿瘤信息\noutput: 肿瘤是良性还是恶行 (两个结果选其一)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Predict categories\nsmall number of possible outpus\n\n已知大量肿瘤信息及其是良性还是恶性的数据\ninput: 肿瘤信息\noutput: 肿瘤是良性还是恶行 (两个结果选其一)",
			"lineHeight": 1.25,
			"baseline": 143
		},
		{
			"type": "arrow",
			"version": 537,
			"versionNonce": 774426864,
			"isDeleted": false,
			"id": "8tRqsb0R10cKeAZK5pQK_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 502.6364526967682,
			"y": -456.65786700346166,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.99999999999999,
			"height": 0,
			"seed": 132129915,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063435,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "iI0EUlEuFOB1EEspp-R5M",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "B0DXYnz5",
				"focus": 0,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.999999999999986,
					0
				],
				[
					88.99999999999999,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 563,
			"versionNonce": 1845318896,
			"isDeleted": false,
			"id": "z1gryULx8-yDPQZIZfcXC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 502.6364526967682,
			"y": -267.7578670034617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.99999999999999,
			"height": 0,
			"seed": 631129077,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063436,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "tIXqoYt7pIyyf6cif5KJS",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "VXQ2ORUv",
				"focus": 0,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.999999999999986,
					0
				],
				[
					88.99999999999999,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 831,
			"versionNonce": 1271365136,
			"isDeleted": false,
			"id": "fKij4jTMEcxLa_lhhahXr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -70.59534334188106,
			"y": -387.1499019672637,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 62.384069927604074,
			"seed": 899045627,
			"groupIds": [
				"eIyBMr71-f6ipshRE7Pti"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "dLE3qzpK"
				},
				{
					"id": "IvWsf1nJ5GO4onCOp4yBn",
					"type": "arrow"
				},
				{
					"id": "FBwUP0Lf1hh3VU2K3LgDV",
					"type": "arrow"
				},
				{
					"id": "QjReOLRGhKsCQEPZ2f5cq",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 599,
			"versionNonce": 1426270960,
			"isDeleted": false,
			"id": "dLE3qzpK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -45.46730308466016,
			"y": -380.9578670034617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 190.8598175048828,
			"height": 50,
			"seed": 1669800469,
			"groupIds": [
				"eIyBMr71-f6ipshRE7Pti"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "supervised learning \n监督学习",
			"rawText": "supervised learning \n监督学习",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fKij4jTMEcxLa_lhhahXr",
			"originalText": "supervised learning \n监督学习",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 1197,
			"versionNonce": 1347238928,
			"isDeleted": false,
			"id": "aL7a3S2Z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -71.42007395425458,
			"y": -443.0323786081266,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 242.8998260498047,
			"height": 50,
			"seed": 1168172955,
			"groupIds": [
				"eIyBMr71-f6ipshRE7Pti"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Learn from data labeled\nwith the \"right answers\"",
			"rawText": "Learn from data labeled\nwith the \"right answers\"",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Learn from data labeled\nwith the \"right answers\"",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 726,
			"versionNonce": 485711088,
			"isDeleted": false,
			"id": "u_CfVIZ9DPqfP4w1YyReM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.35511540948116,
			"y": -154.42453875639137,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 162.7597720676001,
			"height": 157.586007385836,
			"seed": 1952676026,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063439,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "RCtE_NuJ-3fCUi0ViQC96",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "2KxooE3CHe0xd4hRHrYCF",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					113.7597720676001,
					156.6666717529297
				],
				[
					162.7597720676001,
					157.586007385836
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1042,
			"versionNonce": 2037070352,
			"isDeleted": false,
			"id": "2KxooE3CHe0xd4hRHrYCF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -70.59534334188106,
			"y": -25.749901967263725,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 62.384069927604074,
			"seed": 462880762,
			"groupIds": [
				"baALuG7KJ-RtvyGhK8ACM"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "FyMqHPYU"
				},
				{
					"id": "u_CfVIZ9DPqfP4w1YyReM",
					"type": "arrow"
				},
				{
					"id": "tXCND7LUCXN2-21mFnNBy",
					"type": "arrow"
				},
				{
					"id": "AB9ftzFa6xfLXn6_cdH_F",
					"type": "arrow"
				},
				{
					"id": "qkWQWMP5DfTnCf2NM4eUY",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 811,
			"versionNonce": 294203120,
			"isDeleted": false,
			"id": "FyMqHPYU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -55.81729392938672,
			"y": -19.557867003461688,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 211.55979919433594,
			"height": 50,
			"seed": 1332277434,
			"groupIds": [
				"baALuG7KJ-RtvyGhK8ACM"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "unsupervised learning \n无监督学习",
			"rawText": "unsupervised learning \n无监督学习",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "2KxooE3CHe0xd4hRHrYCF",
			"originalText": "unsupervised learning \n无监督学习",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 396,
			"versionNonce": 169441296,
			"isDeleted": false,
			"id": "ObcZHlEV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -69.5737087185721,
			"y": 50.42963438792128,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 340.8397216796875,
			"height": 100,
			"seed": 99377510,
			"groupIds": [
				"baALuG7KJ-RtvyGhK8ACM"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Find something interesting\nin unlabeled data\n\nhas to find structure in the data",
			"rawText": "Find something interesting\nin unlabeled data\n\nhas to find structure in the data",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Find something interesting\nin unlabeled data\n\nhas to find structure in the data",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 983,
			"versionNonce": 1483067632,
			"isDeleted": false,
			"id": "ENtDubxVlEDWTv55VJ8f5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260.52055467744356,
			"y": -123.94990196726371,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 62.384069927604074,
			"seed": 1677895098,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "5TS7ggQw",
					"type": "text"
				},
				{
					"id": "tXCND7LUCXN2-21mFnNBy",
					"type": "arrow"
				},
				{
					"id": "w6mr3Zc2zsOmNZfBj7QyV",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 860,
			"versionNonce": 642774544,
			"isDeleted": false,
			"id": "5TS7ggQw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 335.02855404110977,
			"y": -117.75786700346168,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.09989929199219,
			"height": 50,
			"seed": 1591336570,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "clustering\n聚类",
			"rawText": "clustering\n聚类",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ENtDubxVlEDWTv55VJ8f5",
			"originalText": "clustering\n聚类",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 616,
			"versionNonce": 1017472240,
			"isDeleted": false,
			"id": "tXCND7LUCXN2-21mFnNBy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 104.36983838604854,
			"y": -26.749901967263725,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.150716291395,
			"height": 63.72730066910428,
			"seed": 1204959078,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063440,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "2KxooE3CHe0xd4hRHrYCF",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "ENtDubxVlEDWTv55VJ8f5",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					106.15071629139501,
					-62.80796503619797
				],
				[
					155.150716291395,
					-63.72730066910428
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1038,
			"versionNonce": 856077328,
			"isDeleted": false,
			"id": "ANMgnInMCHc2epvuIuBbx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260.52055467744356,
			"y": -24.557867003461695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 60,
			"seed": 139993702,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "Bpt7t9kU",
					"type": "text"
				},
				{
					"id": "AB9ftzFa6xfLXn6_cdH_F",
					"type": "arrow"
				},
				{
					"id": "0hnN2M0kQREy0ukP2o2rn",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 993,
			"versionNonce": 1828345072,
			"isDeleted": false,
			"id": "Bpt7t9kU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 293.6385775396449,
			"y": -19.557867003461695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 174.87985229492188,
			"height": 50,
			"seed": 590538150,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Anomaly detection\n异常检查",
			"rawText": "Anomaly detection\n异常检查",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ANMgnInMCHc2epvuIuBbx",
			"originalText": "Anomaly detection\n异常检查",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 607,
			"versionNonce": 909488656,
			"isDeleted": false,
			"id": "X3SP5xPy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 591.6364526967682,
			"y": -155.25786700346168,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 476.159912109375,
			"height": 125,
			"seed": 2092993146,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "w6mr3Zc2zsOmNZfBj7QyV",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group similar data points together.\n\n将具有相同关键字的新闻聚到一起, 类似Google News\ninput: 各种新闻文章\noutput: 将相同特性的文章聚在一起.",
			"rawText": "Group similar data points together.\n\n将具有相同关键字的新闻聚到一起, 类似Google News\ninput: 各种新闻文章\noutput: 将相同特性的文章聚在一起.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Group similar data points together.\n\n将具有相同关键字的新闻聚到一起, 类似Google News\ninput: 各种新闻文章\noutput: 将相同特性的文章聚在一起.",
			"lineHeight": 1.25,
			"baseline": 118
		},
		{
			"type": "arrow",
			"version": 617,
			"versionNonce": 224717040,
			"isDeleted": false,
			"id": "AB9ftzFa6xfLXn6_cdH_F",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 171.52055467744358,
			"y": 5.442132996538307,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87.99999999999997,
			"height": 1.7763568394002505e-15,
			"seed": 421870138,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063440,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "2KxooE3CHe0xd4hRHrYCF",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "ANMgnInMCHc2epvuIuBbx",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.99999999999997,
					-1.7763568394002505e-15
				],
				[
					87.99999999999997,
					-1.7763568394002505e-15
				]
			]
		},
		{
			"type": "arrow",
			"version": 530,
			"versionNonce": 2123056880,
			"isDeleted": false,
			"id": "w6mr3Zc2zsOmNZfBj7QyV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 502.6364526967682,
			"y": -92.75786700346168,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.99999999999999,
			"height": 0,
			"seed": 983937849,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063440,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ENtDubxVlEDWTv55VJ8f5",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "X3SP5xPy",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.999999999999986,
					0
				],
				[
					88.99999999999999,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 181,
			"versionNonce": 20830448,
			"isDeleted": false,
			"id": "75pAKB5C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 591.6364526967682,
			"y": -7.057867003461695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 245.63980102539062,
			"height": 25,
			"seed": 301687511,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "0hnN2M0kQREy0ukP2o2rn",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Find unusual data points",
			"rawText": "Find unusual data points",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Find unusual data points",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1172,
			"versionNonce": 484208144,
			"isDeleted": false,
			"id": "WYn84jodtcLPr-DFttTRA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 263.38938092577723,
			"y": 60.937038381056254,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.11589801932462,
			"height": 60,
			"seed": 914694263,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "2mFctrNh",
					"type": "text"
				},
				{
					"id": "1I5SLB_pwJ6LN-cNK43uJ",
					"type": "arrow"
				},
				{
					"id": "qkWQWMP5DfTnCf2NM4eUY",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1209,
			"versionNonce": 2146777840,
			"isDeleted": false,
			"id": "2mFctrNh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 268.6174425453028,
			"y": 65.93703838105625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 230.65977478027344,
			"height": 50,
			"seed": 2014837143,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Dimensionality reduction\n降维",
			"rawText": "Dimensionality reduction\n降维",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WYn84jodtcLPr-DFttTRA",
			"originalText": "Dimensionality reduction\n降维",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 289,
			"versionNonce": 289680400,
			"isDeleted": false,
			"id": "rBJjOVns",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 607.4150134782211,
			"y": 72.69932022191665,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 349.35968017578125,
			"height": 25,
			"seed": 1896492953,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "1I5SLB_pwJ6LN-cNK43uJ",
					"type": "arrow"
				}
			],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Compress data using fewer numbers",
			"rawText": "Compress data using fewer numbers",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Compress data using fewer numbers",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 550,
			"versionNonce": 347753200,
			"isDeleted": false,
			"id": "0hnN2M0kQREy0ukP2o2rn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 502.6364526967682,
			"y": 5.442132996538305,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89,
			"height": 0,
			"seed": 1966447097,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063441,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ANMgnInMCHc2epvuIuBbx",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "75pAKB5C",
				"focus": 0,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					39,
					0
				],
				[
					89,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 804,
			"versionNonce": 252931312,
			"isDeleted": false,
			"id": "1I5SLB_pwJ6LN-cNK43uJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 507.65690683916114,
			"y": 88.00701747990253,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.09200661286991,
			"height": 6.393721860593887,
			"seed": 571517273,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063443,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WYn84jodtcLPr-DFttTRA",
				"gap": 3.1516278940592883,
				"focus": 0.3486647218817362
			},
			"endBinding": {
				"elementId": "rBJjOVns",
				"focus": 0.23094706195325146,
				"gap": 10.666100026190122
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					39.000032831236126,
					-6.393721860593887
				],
				[
					89.09200661286991,
					-6.266723310727816
				]
			]
		},
		{
			"type": "arrow",
			"version": 795,
			"versionNonce": 1710771952,
			"isDeleted": false,
			"id": "qkWQWMP5DfTnCf2NM4eUY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 164.8223191841233,
			"y": 37.63416796034035,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.56706174165393,
			"height": 24.919262200131307,
			"seed": 240471767,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063443,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "2KxooE3CHe0xd4hRHrYCF",
				"gap": 1,
				"focus": 0
			},
			"endBinding": {
				"elementId": "WYn84jodtcLPr-DFttTRA",
				"gap": 1,
				"focus": 0
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					45.698235493320254,
					12.807965036197956
				],
				[
					97.56706174165393,
					24.919262200131307
				]
			]
		},
		{
			"type": "text",
			"version": 415,
			"versionNonce": 1309960208,
			"isDeleted": false,
			"id": "LqRXJMJO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -306.20203979022244,
			"y": 342.28595162107456,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 909.6193237304688,
			"height": 50,
			"seed": 1247864379,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "# The Terminology\ntraining set, feature, target, m=number of training examples, (x, y) = single training example",
			"rawText": "# The Terminology\ntraining set, feature, target, m=number of training examples, (x, y) = single training example",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "# The Terminology\ntraining set, feature, target, m=number of training examples, (x, y) = single training example",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 710,
			"versionNonce": 433185008,
			"isDeleted": false,
			"id": "WwMoVUVy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -268.93129540801806,
			"y": 1256.179198753757,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 916.2596435546875,
			"height": 75,
			"seed": 246236265,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "# Linear regression\n\n回归模型属于监督学习, 提供正确的feature和target大量数据, 让model拟合出一条linear regression. ",
			"rawText": "# Linear regression\n\n回归模型属于监督学习, 提供正确的feature和target大量数据, 让model拟合出一条linear regression. ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "# Linear regression\n\n回归模型属于监督学习, 提供正确的feature和target大量数据, 让model拟合出一条linear regression. ",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "text",
			"version": 610,
			"versionNonce": 225240592,
			"isDeleted": false,
			"id": "hwbVWO9k",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -46.976664776035705,
			"y": 1224.130421242117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 738.8593139648438,
			"height": 50,
			"seed": 1341371143,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Regression model, predicts numbers, infinitely many possible outputs.\nClassification model, predicts categories, small number of possible outputs.",
			"rawText": "Regression model, predicts numbers, infinitely many possible outputs.\nClassification model, predicts categories, small number of possible outputs.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Regression model, predicts numbers, infinitely many possible outputs.\nClassification model, predicts categories, small number of possible outputs.",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 232,
			"versionNonce": 2026390256,
			"isDeleted": false,
			"id": "mW8uERUI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -330.9033004209773,
			"y": -567.4148589569163,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 303.4197692871094,
			"height": 25,
			"seed": 1756866793,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "# Mindmap for machine learning",
			"rawText": "# Mindmap for machine learning",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "# Mindmap for machine learning",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 384,
			"versionNonce": 151364624,
			"isDeleted": false,
			"id": "XvUB6fTvVYKr9-Uljbnnz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -262.85292166510055,
			"y": 1350.825742546841,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1263.5634028892448,
			"height": 624.7619047619044,
			"seed": 571944743,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "459241ea8e1099fc927ef98a2b17754fe1ead925",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 782394608,
			"isDeleted": false,
			"id": "u0pu0q5h",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -244.9642125051073,
			"y": 2137.0903302982715,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 160.37986755371094,
			"height": 25,
			"seed": 1912570407,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "# Cost Function",
			"rawText": "# Cost Function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "# Cost Function",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 1021,
			"versionNonce": 1322689040,
			"isDeleted": false,
			"id": "NUGCTc8u",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -240.54112283061158,
			"y": 2171.848151417708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 741.5997314453125,
			"height": 150,
			"seed": 1129281865,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Cost, 一个线性回归模型, linear方程, 预测targets和实际的targets之间的平方差.\n\n为什么要计算Cost?\n为了拟合一条cost最小的linear regression. cost越小, 越接近真实的targets.\n\n",
			"rawText": "Cost, 一个线性回归模型, linear方程, 预测targets和实际的targets之间的平方差.\n\n为什么要计算Cost?\n为了拟合一条cost最小的linear regression. cost越小, 越接近真实的targets.\n\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Cost, 一个线性回归模型, linear方程, 预测targets和实际的targets之间的平方差.\n\n为什么要计算Cost?\n为了拟合一条cost最小的linear regression. cost越小, 越接近真实的targets.\n\n",
			"lineHeight": 1.25,
			"baseline": 143
		},
		{
			"type": "image",
			"version": 1037,
			"versionNonce": 686311152,
			"isDeleted": false,
			"id": "IqAnivRDaYjbJJu4Q2hPY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -238.09113226523982,
			"y": 2287.777599508878,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 570.8339715730699,
			"height": 390.1016996368917,
			"seed": 475385897,
			"groupIds": [
				"fXosko3eCRJauGr4cyb7K"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f195d58f23ad3daabbf4ca59dd40f2b2f7a93f52",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 847,
			"versionNonce": 1842864144,
			"isDeleted": false,
			"id": "gtjX9QWv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -222.18308796429267,
			"y": 2393.152312265225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.8269805908203,
			"height": 15.90953098029738,
			"seed": 2127165447,
			"groupIds": [
				"fXosko3eCRJauGr4cyb7K"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 12.727624784237904,
			"fontFamily": 1,
			"text": "w, b 被称为Parameter",
			"rawText": "w, b 被称为Parameter",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "w, b 被称为Parameter",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "image",
			"version": 777,
			"versionNonce": 1679943920,
			"isDeleted": false,
			"id": "BYguYNIMOezIEv6NNP7Ln",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -244.4092841275808,
			"y": 2848.9614412885057,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 856.7527027971033,
			"height": 433.85430985633366,
			"seed": 1102322439,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8337d91000e7188fa033f0b45cb121abaa361a0f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 437,
			"versionNonce": 1442930192,
			"isDeleted": false,
			"id": "roCdQqPcCMVo_LYmfZSO5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 542.996805967746,
			"y": 2158.3780127223554,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 472.3964904726373,
			"height": 218.675036934397,
			"seed": 1246800999,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "85947bf193769b617848e7e73862f0e26eb4993f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 319,
			"versionNonce": 198658800,
			"isDeleted": false,
			"id": "0CkyQn0K",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -238.67375729587832,
			"y": 2748.8429558126604,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 583.2198486328125,
			"height": 75,
			"seed": 1993151337,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "如何计算并得到最小Cost的linear regression model?\n首先, 我们简化, 只有一个w, b=0.\n当只有一个parameter, w时, J(w)的Cost函数, 其实就是斜率函数",
			"rawText": "如何计算并得到最小Cost的linear regression model?\n首先, 我们简化, 只有一个w, b=0.\n当只有一个parameter, w时, J(w)的Cost函数, 其实就是斜率函数",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "如何计算并得到最小Cost的linear regression model?\n首先, 我们简化, 只有一个w, b=0.\n当只有一个parameter, w时, J(w)的Cost函数, 其实就是斜率函数",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "text",
			"version": 390,
			"versionNonce": 944446480,
			"isDeleted": false,
			"id": "m86LMwqL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -225.5966812019317,
			"y": 3349.298699793024,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 743.83984375,
			"height": 25,
			"seed": 270360903,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "接下来, 我们将b添加回来, 这样就会有两个parameter, 同样J(w)的cost可视化如下.",
			"rawText": "接下来, 我们将b添加回来, 这样就会有两个parameter, 同样J(w)的cost可视化如下.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "接下来, 我们将b添加回来, 这样就会有两个parameter, 同样J(w)的cost可视化如下.",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 489,
			"versionNonce": 445672688,
			"isDeleted": false,
			"id": "aqnen8nFKyo2gpg1EpPtu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -273.20259239395637,
			"y": 3380.9016336867276,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1064.0052096772322,
			"height": 593.844934462181,
			"seed": 1801913897,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "adc7bf209aeb9887831b5a19e30b56ade31ebd6b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 1722620432,
			"isDeleted": false,
			"id": "iRYKytWy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -247.39180802517524,
			"y": 4118.666676653525,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 200.0198516845703,
			"height": 25,
			"seed": 1868944489,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "# Gradient Descent",
			"rawText": "# Gradient Descent",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "# Gradient Descent",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 595,
			"versionNonce": 2044022512,
			"isDeleted": false,
			"id": "k6pCMJi9bfsYnlcU_-Sn1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 516.6087183994052,
			"y": 4193.745824188854,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 676.8346557827581,
			"height": 368.96889221490636,
			"seed": 1773560393,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "12650067943434d41549f17e2f0184a32249b9ef",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 965,
			"versionNonce": 874469392,
			"isDeleted": false,
			"id": "cZWstGyR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -237.17651317552009,
			"y": 4159.434382861598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 655.760009765625,
			"height": 250,
			"seed": 641048873,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "梯度下降\n\n比喻一下, 就是一个人在凹凸不平的山林, 从高点走到最低点.\n1. 从一个点开始, 每次360度看一圈, 找一个坡度下降最大的点, 向下走.\n2. 不断重复步骤1, 直到到达最低点.\n3. 从另一个点开始, 重复1,2步骤, 达到最低点.\n\n如图的两条路径, 最终到达的都是local minima, 局部最低点.\n\n其次, 梯度下降的特性, 就是分别从两个出发点到达的最低点是相互不知的.",
			"rawText": "梯度下降\n\n比喻一下, 就是一个人在凹凸不平的山林, 从高点走到最低点.\n1. 从一个点开始, 每次360度看一圈, 找一个坡度下降最大的点, 向下走.\n2. 不断重复步骤1, 直到到达最低点.\n3. 从另一个点开始, 重复1,2步骤, 达到最低点.\n\n如图的两条路径, 最终到达的都是local minima, 局部最低点.\n\n其次, 梯度下降的特性, 就是分别从两个出发点到达的最低点是相互不知的.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "梯度下降\n\n比喻一下, 就是一个人在凹凸不平的山林, 从高点走到最低点.\n1. 从一个点开始, 每次360度看一圈, 找一个坡度下降最大的点, 向下走.\n2. 不断重复步骤1, 直到到达最低点.\n3. 从另一个点开始, 重复1,2步骤, 达到最低点.\n\n如图的两条路径, 最终到达的都是local minima, 局部最低点.\n\n其次, 梯度下降的特性, 就是分别从两个出发点到达的最低点是相互不知的.",
			"lineHeight": 1.25,
			"baseline": 243
		},
		{
			"type": "text",
			"version": 881,
			"versionNonce": 573436144,
			"isDeleted": false,
			"id": "F2q0HB3N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.71796484693994,
			"y": 4436.047975576132,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 670.6998291015625,
			"height": 200,
			"seed": 1382503335,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "learning rate, 控制下降步子的大小, 调整参数, 步长.\nderivative term, 导数项(来自微积分)(偏导), 朝哪个方向迈出婴儿步, 方向.\npartial derivative, 偏导数\n\nrepeat util convergence, 重复到收敛\n\nw, b需要同步更新, 而不是更新好w立刻作为更新b的输入.\n",
			"rawText": "learning rate, 控制下降步子的大小, 调整参数, 步长.\nderivative term, 导数项(来自微积分)(偏导), 朝哪个方向迈出婴儿步, 方向.\npartial derivative, 偏导数\n\nrepeat util convergence, 重复到收敛\n\nw, b需要同步更新, 而不是更新好w立刻作为更新b的输入.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "learning rate, 控制下降步子的大小, 调整参数, 步长.\nderivative term, 导数项(来自微积分)(偏导), 朝哪个方向迈出婴儿步, 方向.\npartial derivative, 偏导数\n\nrepeat util convergence, 重复到收敛\n\nw, b需要同步更新, 而不是更新好w立刻作为更新b的输入.\n",
			"lineHeight": 1.25,
			"baseline": 193
		},
		{
			"type": "image",
			"version": 550,
			"versionNonce": 1419367952,
			"isDeleted": false,
			"id": "prOUEkIID5vLxziEwEVmt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -244.89651193557825,
			"y": 4624.859821187349,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 995.1131383841143,
			"height": 494.1013152393345,
			"seed": 1488723815,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449720,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "465fdf1a18bfd9e1271ec8e06b01603435f6124d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 241,
			"versionNonce": 992105200,
			"isDeleted": false,
			"id": "WLQ1pSxgoqzTlBdIs63j4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -307.9093280857189,
			"y": 414.39516254440787,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1397.7298364354206,
			"height": 674.3333333333335,
			"seed": 1914650247,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8ac4ed5bd704af915d55c1675b727ac02e4019b9",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 799,
			"versionNonce": 1024758800,
			"isDeleted": false,
			"id": "dUbkEhbc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -236.64000323052608,
			"y": 5236.314940108996,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 738.0999755859375,
			"height": 25,
			"seed": 582901066,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "如果我们把导数部分提取出来, 从其结果的正负如何影响到w和b, 就能理解梯度下降.",
			"rawText": "如果我们把导数部分提取出来, 从其结果的正负如何影响到w和b, 就能理解梯度下降.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "如果我们把导数部分提取出来, 从其结果的正负如何影响到w和b, 就能理解梯度下降.",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 399,
			"versionNonce": 993686768,
			"isDeleted": false,
			"id": "WU6I4DFWr0Zed8labLMHe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -211.3280308834219,
			"y": 5279.941030356787,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 846.6310906763134,
			"height": 451.1803197382337,
			"seed": 368987082,
			"groupIds": [
				"duYU5rtFf-_0n-HZbmj4x"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "7cdf04f5d38c4fb6eabcab34502fb6882d0e47e2",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 476,
			"versionNonce": 59216400,
			"isDeleted": false,
			"id": "CSlMJxyv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -165.75733997658824,
			"y": 5736.808628238417,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 210.4263916015625,
			"height": 47.785850757519526,
			"seed": 1026758102,
			"groupIds": [
				"duYU5rtFf-_0n-HZbmj4x"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 12.74289353533854,
			"fontFamily": 1,
			"text": "why -2?\n右边的点减去左边的点.\n导数主要是通过dw/dJ(w)计算得到的.",
			"rawText": "why -2?\n右边的点减去左边的点.\n导数主要是通过dw/dJ(w)计算得到的.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "why -2?\n右边的点减去左边的点.\n导数主要是通过dw/dJ(w)计算得到的.",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "text",
			"version": 240,
			"versionNonce": 134108912,
			"isDeleted": false,
			"id": "HvJSKflL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -235.55545553394688,
			"y": 5198.253453974452,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142.27987670898438,
			"height": 25,
			"seed": 144139361,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "## Derivative",
			"rawText": "## Derivative",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "## Derivative",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 258,
			"versionNonce": 1055576080,
			"isDeleted": false,
			"id": "FawvxES3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -233.8636037381102,
			"y": 5824.176906696153,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 173.9998779296875,
			"height": 25,
			"seed": 1063195376,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "## Learning rate",
			"rawText": "## Learning rate",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "## Learning rate",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 376,
			"versionNonce": 368441584,
			"isDeleted": false,
			"id": "he6JacwB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -227.23395037853538,
			"y": 5878.68738987488,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 240.6199951171875,
			"height": 75,
			"seed": 1846992112,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "学习率, 控制步长. \n过大, 导致无法到达最低点.\n过小, 梯度下降速度慢.",
			"rawText": "学习率, 控制步长. \n过大, 导致无法到达最低点.\n过小, 梯度下降速度慢.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "学习率, 控制步长. \n过大, 导致无法到达最低点.\n过小, 梯度下降速度慢.",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "image",
			"version": 337,
			"versionNonce": 1731612176,
			"isDeleted": false,
			"id": "CCGxiBVDssd9jd4idoJAU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 47.87774125871806,
			"y": 5852.9312447223565,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 257.69520529955287,
			"height": 175.04624965249235,
			"seed": 955158544,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f2fcb088d2b5770eb474aa03213f3df2be037ee2",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 372,
			"versionNonce": 145316592,
			"isDeleted": false,
			"id": "AGjz-iMLRHF7UPsFwGswv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 343.7526050125397,
			"y": 5845.933441076602,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 286.5312364207834,
			"height": 182.2138228431055,
			"seed": 1951429360,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "be38fa6e70dfe4040fa25af4b10dea84d6a33383",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 1756,
			"versionNonce": 895618064,
			"isDeleted": false,
			"id": "Dp1niPs3_gABtM4R7VgJp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2328.496467219835,
			"y": 683.1289105512537,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 264.51776422915776,
			"height": 92.77993424203403,
			"seed": 1295348976,
			"groupIds": [
				"392pOkyZnCMWi-u7rrvGt",
				"Myidj3YXtePrTSSNnP3n2"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "gqVSM8mb"
				},
				{
					"id": "UkadM-C2o4NSx6XlHuSix",
					"type": "arrow"
				}
			],
			"updated": 1701503449721,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1353,
			"versionNonce": 1386249456,
			"isDeleted": false,
			"id": "gqVSM8mb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2305.6374798196116,
			"y": 688.1289105512537,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 218.79978942871094,
			"height": 25,
			"seed": 580474608,
			"groupIds": [
				"392pOkyZnCMWi-u7rrvGt",
				"Myidj3YXtePrTSSNnP3n2"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "linear regression model",
			"rawText": "linear regression model",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": "Dp1niPs3_gABtM4R7VgJp",
			"originalText": "linear regression model",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 1293,
			"versionNonce": 57018896,
			"isDeleted": false,
			"id": "RZTE9JtmU0iAwoXcIiGAC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2283.3624939497813,
			"y": 722.1658584084557,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 173.69410810033554,
			"height": 42.51508503711142,
			"seed": 623966448,
			"groupIds": [
				"392pOkyZnCMWi-u7rrvGt",
				"Myidj3YXtePrTSSNnP3n2"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d36759399429b17971c894122d88910bbfeb66d1",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 1241,
			"versionNonce": 1432575728,
			"isDeleted": false,
			"id": "grNoZ0fO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2475.203798641048,
			"y": 707.0244228660654,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 217.91998291015625,
			"height": 100,
			"seed": 2021939952,
			"groupIds": [
				"Myidj3YXtePrTSSNnP3n2"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "获取最适合的\n线性回归模型\n\n最适合 -> 预测误差最小",
			"rawText": "获取最适合的\n线性回归模型\n\n最适合 -> 预测误差最小",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "获取最适合的\n线性回归模型\n\n最适合 -> 预测误差最小",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "text",
			"version": 1657,
			"versionNonce": 742017040,
			"isDeleted": false,
			"id": "7f7U5gAg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2485.5705629057848,
			"y": 429.3081696424274,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 136.01995849609375,
			"height": 100,
			"seed": 253459696,
			"groupIds": [
				"hvf_R_U5ngEwT8f4H_usq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "获取最小成本\n均方误差(MSE)\n\n计算, w, b",
			"rawText": "获取最小成本\n均方误差(MSE)\n\n计算, w, b",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "获取最小成本\n均方误差(MSE)\n\n计算, w, b",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 1988,
			"versionNonce": 24772848,
			"isDeleted": false,
			"id": "VRSE2yb1Wu68RQDyP9XG7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2344.564514642203,
			"y": 422.00067976978926,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 264.51776422915776,
			"height": 92.77993424203403,
			"seed": 1249795824,
			"groupIds": [
				"tQ6OtkDSGEp8PfBafSTIj",
				"hvf_R_U5ngEwT8f4H_usq"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "0MebN1T3"
				},
				{
					"id": "UkadM-C2o4NSx6XlHuSix",
					"type": "arrow"
				},
				{
					"id": "MXKWF2hrLnjvfZRMWkKrs",
					"type": "arrow"
				}
			],
			"updated": 1701503449721,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1598,
			"versionNonce": 1809237520,
			"isDeleted": false,
			"id": "0MebN1T3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2278.6455678303587,
			"y": 427.00067976978926,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.67987060546875,
			"height": 25,
			"seed": 456458480,
			"groupIds": [
				"tQ6OtkDSGEp8PfBafSTIj",
				"hvf_R_U5ngEwT8f4H_usq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Cost function",
			"rawText": "Cost function",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": "VRSE2yb1Wu68RQDyP9XG7",
			"originalText": "Cost function",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 1499,
			"versionNonce": 1986814704,
			"isDeleted": false,
			"id": "hX9VuoGoRAy9jnWYWfGl9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2332.1193532338652,
			"y": 454.0757975368083,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 242.81762608845187,
			"height": 50.302372667940155,
			"seed": 549937904,
			"groupIds": [
				"tQ6OtkDSGEp8PfBafSTIj",
				"hvf_R_U5ngEwT8f4H_usq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3e46a8289c0beef4b7743fb67296db0fc0f402ca",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 1165,
			"versionNonce": 1060340752,
			"isDeleted": false,
			"id": "aI9NiDKirLXBqoGW3magI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2341.252975408812,
			"y": -236.5352807031444,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 201.8933252978752,
			"height": 86.71269238887672,
			"seed": 1237157104,
			"groupIds": [
				"sDfyyxBI-QC-aCESrEncY",
				"H_csyxbpWT86cJimpYfdn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f18200570d2c24aeccde046e2775efc0dba9c54f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 1693,
			"versionNonce": 583173360,
			"isDeleted": false,
			"id": "b1Tkgz1_FhmfJ5UE7UkGR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2372.291534114728,
			"y": -270.5566913454353,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 264.51776422915776,
			"height": 132.2353150409209,
			"seed": 1939826416,
			"groupIds": [
				"sDfyyxBI-QC-aCESrEncY",
				"H_csyxbpWT86cJimpYfdn"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "JMBNnIa6"
				},
				{
					"id": "7Eax9fsSrAPzmThXRufqX",
					"type": "arrow"
				},
				{
					"id": "SAXOEuDqINuOGrDPyOIBG",
					"type": "arrow"
				},
				{
					"id": "B2DgsMCe9aCKDQjzCeAdG",
					"type": "arrow"
				}
			],
			"updated": 1701503449721,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1321,
			"versionNonce": 1145602576,
			"isDeleted": false,
			"id": "JMBNnIa6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2324.9625836407745,
			"y": -265.5566913454353,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.85986328125,
			"height": 25,
			"seed": 183830768,
			"groupIds": [
				"sDfyyxBI-QC-aCESrEncY",
				"H_csyxbpWT86cJimpYfdn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Gradient descent",
			"rawText": "Gradient descent",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": "b1Tkgz1_FhmfJ5UE7UkGR",
			"originalText": "Gradient descent",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 1429,
			"versionNonce": 1678010096,
			"isDeleted": false,
			"id": "DH52eNQ0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2562.217069366325,
			"y": -251.21845715882455,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 162.33998107910156,
			"height": 100,
			"seed": 726035184,
			"groupIds": [
				"H_csyxbpWT86cJimpYfdn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "梯度下降算法\n计算最小成本\n同时更新, wb\n直到w和b停止更新",
			"rawText": "梯度下降算法\n计算最小成本\n同时更新, wb\n直到w和b停止更新",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "梯度下降算法\n计算最小成本\n同时更新, wb\n直到w和b停止更新",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 2052,
			"versionNonce": 437108752,
			"isDeleted": false,
			"id": "CIG1pVbBD6cfZ0mZGPZIJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2601.1939210660357,
			"y": -599.738767669879,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 264.51776422915776,
			"height": 132.2353150409209,
			"seed": 1058770160,
			"groupIds": [
				"7k3zTk_74Ls5-_ljuLcH7"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "1e9c8ZB9"
				},
				{
					"id": "SAXOEuDqINuOGrDPyOIBG",
					"type": "arrow"
				},
				{
					"id": "zc-PnxeV74MlOgAgt5p4l",
					"type": "arrow"
				}
			],
			"updated": 1701503449721,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1694,
			"versionNonce": 649726192,
			"isDeleted": false,
			"id": "1e9c8ZB9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2519.134990123332,
			"y": -594.738767669879,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.39990234375,
			"height": 25,
			"seed": 536637168,
			"groupIds": [
				"7k3zTk_74Ls5-_ljuLcH7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Derivative",
			"rawText": "Derivative",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": "CIG1pVbBD6cfZ0mZGPZIJ",
			"originalText": "Derivative",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 1614,
			"versionNonce": 1081818640,
			"isDeleted": false,
			"id": "RPBy7xOb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2580.200953464397,
			"y": -536.2722733457887,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 913379568,
			"groupIds": [
				"7k3zTk_74Ls5-_ljuLcH7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "导数",
			"rawText": "导数",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "导数",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "image",
			"version": 1109,
			"versionNonce": 107703024,
			"isDeleted": false,
			"id": "6Uovs2Qk8VzWB3XqTGnQ8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2522.96478403871,
			"y": -558.9670734759258,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 138.5615740406347,
			"height": 68.58098109081918,
			"seed": 436302576,
			"groupIds": [
				"7k3zTk_74Ls5-_ljuLcH7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2008f6569c530f6be24d92dc8aa5fdf89006403a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 2392,
			"versionNonce": 384518384,
			"isDeleted": false,
			"id": "uFXZRQSQS_UyARBTqV_Is",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2154.2693475680603,
			"y": -587.7078640504901,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.18638879588687,
			"height": 112.65574856072283,
			"seed": 825595120,
			"groupIds": [
				"Ai0ndCBjOLNI6H-iu4AGu"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "UdnmFRTQ",
					"type": "text"
				},
				{
					"id": "B2DgsMCe9aCKDQjzCeAdG",
					"type": "arrow"
				},
				{
					"id": "IBDr7zQgfbI17gBLHVACR",
					"type": "arrow"
				},
				{
					"id": "Z0hdrFck5Idt9KTjUbKUg",
					"type": "arrow"
				}
			],
			"updated": 1701503456918,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2105,
			"versionNonce": 1839238384,
			"isDeleted": false,
			"id": "UdnmFRTQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2109.995405184277,
			"y": -582.7078640504901,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 152.6385040283203,
			"height": 27.846939688413983,
			"seed": 1368749808,
			"groupIds": [
				"Ai0ndCBjOLNI6H-iu4AGu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 22.277551750731185,
			"fontFamily": 1,
			"text": "Learning Rate",
			"rawText": "Learning Rate",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": "uFXZRQSQS_UyARBTqV_Is",
			"originalText": "Learning Rate",
			"lineHeight": 1.25,
			"baseline": 19
		},
		{
			"type": "image",
			"version": 1075,
			"versionNonce": 607058448,
			"isDeleted": false,
			"id": "mXmVeN5i5-w2H7qoKc6Zw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2061.7490128571712,
			"y": -544.8696368458309,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 60.849673159122645,
			"height": 60.849673159122645,
			"seed": 1604917488,
			"groupIds": [
				"Ai0ndCBjOLNI6H-iu4AGu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "233023fdf05efd38b016a66dd94eda3139d13e14",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 1677,
			"versionNonce": 903966448,
			"isDeleted": false,
			"id": "CiKLrdKJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2141.0600370591897,
			"y": -532.5545542570685,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 25,
			"seed": 1861778160,
			"groupIds": [
				"Ai0ndCBjOLNI6H-iu4AGu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "学习率",
			"rawText": "学习率",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "学习率",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2337,
			"versionNonce": 1252087536,
			"isDeleted": false,
			"id": "UkadM-C2o4NSx6XlHuSix",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2254.478032711504,
			"y": 669.3469551282287,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.0394899370439816,
			"height": 144.34677301059833,
			"seed": 1644928240,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "mCd6YIsw"
				}
			],
			"updated": 1701504063444,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Dp1niPs3_gABtM4R7VgJp",
				"gap": 13.781955423024954,
				"focus": -0.42761370909054136
			},
			"endBinding": {
				"elementId": "VRSE2yb1Wu68RQDyP9XG7",
				"gap": 10.219568105807042,
				"focus": 0.3482843264259995
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-3.0394899370439816,
					-144.34677301059833
				]
			]
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1203114224,
			"isDeleted": false,
			"id": "mCd6YIsw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2706.0918461878528,
			"y": 235.50295432180565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 160,
			"height": 50,
			"seed": 174751472,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "为了预测误差最小\n计算适合的w和b",
			"rawText": "为了预测误差最小\n计算适合的w和b",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UkadM-C2o4NSx6XlHuSix",
			"originalText": "为了预测误差最小\n计算适合的w和b",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "image",
			"version": 1249,
			"versionNonce": 1126413840,
			"isDeleted": false,
			"id": "ppnxN1D2nUrSyW70E1Rmf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1912.9901863733285,
			"y": -206.78411718117195,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 396.60991134193773,
			"height": 404.248324449264,
			"seed": 1218257136,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "7Eax9fsSrAPzmThXRufqX",
					"type": "arrow"
				},
				{
					"id": "MXKWF2hrLnjvfZRMWkKrs",
					"type": "arrow"
				}
			],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "6f88a8d19f4faadb1dc86ce467d10999b4abe029",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "arrow",
			"version": 2171,
			"versionNonce": 1049385712,
			"isDeleted": false,
			"id": "7Eax9fsSrAPzmThXRufqX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1926.9418055536366,
			"y": 23.006941888114397,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 344.3846795971408,
			"height": 139.45809813095667,
			"seed": 741049072,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "O6Qsmhzu"
				}
			],
			"updated": 1701504063446,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ppnxN1D2nUrSyW70E1Rmf",
				"focus": -0.19424553964228894,
				"gap": 13.951619180308171
			},
			"endBinding": {
				"elementId": "b1Tkgz1_FhmfJ5UE7UkGR",
				"gap": 21.870220061672114,
				"focus": 0.41817403112933504
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-296.76613706058225,
					-19.80554222052251
				],
				[
					-344.3846795971408,
					-139.45809813095667
				]
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 2137158672,
			"isDeleted": false,
			"id": "O6Qsmhzu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2758.38168125366,
			"y": -345.9692146335319,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120,
			"height": 25,
			"seed": 329098480,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "获取局部最小",
			"rawText": "获取局部最小",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "7Eax9fsSrAPzmThXRufqX",
			"originalText": "获取局部最小",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1832,
			"versionNonce": 205060336,
			"isDeleted": false,
			"id": "MXKWF2hrLnjvfZRMWkKrs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2068.4461887878215,
			"y": 474.8826771148788,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 309.612916580212,
			"height": 267.2860572201275,
			"seed": 1283163888,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ij9sq61b"
				}
			],
			"updated": 1701504063445,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "VRSE2yb1Wu68RQDyP9XG7",
				"gap": 11.600561625223463,
				"focus": 0.35990770356906543
			},
			"endBinding": {
				"elementId": "ppnxN1D2nUrSyW70E1Rmf",
				"focus": 0.07115589997161709,
				"gap": 10.132412626659232
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					278.0954198282935,
					-29.480079840460775
				],
				[
					309.612916580212,
					-267.2860572201275
				]
			]
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 18444816,
			"isDeleted": false,
			"id": "ij9sq61b",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3221.738854908351,
			"y": 96.23198297329418,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 25,
			"seed": 860694768,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "可视化",
			"rawText": "可视化",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "MXKWF2hrLnjvfZRMWkKrs",
			"originalText": "可视化",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 889,
			"versionNonce": 1291482864,
			"isDeleted": false,
			"id": "NCdZsQqy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2523.422087658847,
			"y": 64.12689800452381,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 544.81982421875,
			"height": 100,
			"seed": 1402637040,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "为什么要使用梯度下降?\n\n仔细看右边的图, \nLinear regression是一个典型的凸函数, 全局只有一个最低点.",
			"rawText": "为什么要使用梯度下降?\n\n仔细看右边的图, \nLinear regression是一个典型的凸函数, 全局只有一个最低点.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "为什么要使用梯度下降?\n\n仔细看右边的图, \nLinear regression是一个典型的凸函数, 全局只有一个最低点.",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "text",
			"version": 722,
			"versionNonce": 1866510352,
			"isDeleted": false,
			"id": "ri2PVrnZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2311.0899367567376,
			"y": 198.51504287978764,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 233.11985778808594,
			"height": 25,
			"seed": 132885744,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "凸函数, Convex function.",
			"rawText": "凸函数, Convex function.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "凸函数, Convex function.",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1875,
			"versionNonce": 329737968,
			"isDeleted": false,
			"id": "SAXOEuDqINuOGrDPyOIBG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2296.3322744787274,
			"y": -284.4838292549963,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 146.70614569631698,
			"height": 166.78253770544598,
			"seed": 202139152,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063447,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "b1Tkgz1_FhmfJ5UE7UkGR",
				"gap": 13.927137909560997,
				"focus": 0.07409915913916555
			},
			"endBinding": {
				"elementId": "CIG1pVbBD6cfZ0mZGPZIJ",
				"gap": 16.23708566851593,
				"focus": 0.24443479966659354
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-146.70614569631698,
					-166.78253770544598
				]
			]
		},
		{
			"type": "arrow",
			"version": 1687,
			"versionNonce": 2080665328,
			"isDeleted": false,
			"id": "B2DgsMCe9aCKDQjzCeAdG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2211.25847397476,
			"y": -294.35983938044944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 145.57115520293019,
			"height": 159.00475992766815,
			"seed": 1356171280,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701504063448,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "b1Tkgz1_FhmfJ5UE7UkGR",
				"gap": 23.803148035014146,
				"focus": -0.27776059527655267
			},
			"endBinding": {
				"elementId": "uFXZRQSQS_UyARBTqV_Is",
				"gap": 21.687516181649755,
				"focus": -0.22892979321907211
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					145.57115520293019,
					-159.00475992766815
				]
			]
		},
		{
			"type": "text",
			"version": 827,
			"versionNonce": 1544999952,
			"isDeleted": false,
			"id": "CQWGamPd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1825.5503034700064,
			"y": -507.920533492672,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 519.1800537109375,
			"height": 50,
			"seed": 1074586640,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701503458849,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "因为是凸函数, 所以学习率固定, 偏导数会随着斜率趋于0, \n最终, 也能到达最低点.",
			"rawText": "因为是凸函数, 所以学习率固定, 偏导数会随着斜率趋于0, \n最终, 也能到达最低点.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "因为是凸函数, 所以学习率固定, 偏导数会随着斜率趋于0, \n最终, 也能到达最低点.",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"id": "W7u1JCQGn9PzH66mC0U_Z",
			"type": "image",
			"x": -2666.970485389721,
			"y": -929.634733519332,
			"width": 306.7272727272723,
			"height": 183.70831307729676,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 250271472,
			"version": 104,
			"versionNonce": 1538592272,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "zc-PnxeV74MlOgAgt5p4l",
					"type": "arrow"
				},
				{
					"id": "2fEk8pTnmf5YD2psjiOgY",
					"type": "arrow"
				}
			],
			"updated": 1701504079669,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d765776dc384508428e3fda18bbc739b5180d098",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 400,
			"versionNonce": 194744560,
			"isDeleted": false,
			"id": "ktaL-ST8nRNkOM2-21K2M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2101.1213849853957,
			"y": -933.86790756715,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 286.5312364207834,
			"height": 182.2138228431055,
			"seed": 1034766352,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "IBDr7zQgfbI17gBLHVACR",
					"type": "arrow"
				},
				{
					"id": "yTFJ2vwlXmq2tOLFbqPyQ",
					"type": "arrow"
				}
			],
			"updated": 1701504087779,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "be38fa6e70dfe4040fa25af4b10dea84d6a33383",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "zc-PnxeV74MlOgAgt5p4l",
			"type": "arrow",
			"x": -2469.4719283911654,
			"y": -615.4882688728692,
			"width": 29.090909090909463,
			"height": 116.36363636363649,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 187335184,
			"version": 49,
			"versionNonce": 1766746864,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "ifuaFQJO"
				}
			],
			"updated": 1701504063447,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-29.090909090909463,
					-116.36363636363649
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "CIG1pVbBD6cfZ0mZGPZIJ",
				"gap": 15.749501202990075,
				"focus": 0.13394803698061525
			},
			"endBinding": {
				"elementId": "W7u1JCQGn9PzH66mC0U_Z",
				"gap": 14.074515205529622,
				"focus": 0.06486893673485443
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "ifuaFQJO",
			"type": "text",
			"x": -2504.0173829366204,
			"y": -686.1700870546874,
			"width": 40,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1151910928,
			"version": 3,
			"versionNonce": 726630128,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"text": "斜率",
			"rawText": "斜率",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 18,
			"containerId": "zc-PnxeV74MlOgAgt5p4l",
			"originalText": "斜率",
			"lineHeight": 1.25
		},
		{
			"id": "IBDr7zQgfbI17gBLHVACR",
			"type": "arrow",
			"x": -2013.2552545421395,
			"y": -593.9125112971116,
			"width": 42.22222222222217,
			"height": 142.22222222222217,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 871786000,
			"version": 45,
			"versionNonce": 336163568,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "tTtno8Ht"
				}
			],
			"updated": 1701504063448,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					42.22222222222217,
					-142.22222222222217
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "uFXZRQSQS_UyARBTqV_Is",
				"gap": 6.204647246621391,
				"focus": 0.013520366353321664
			},
			"endBinding": {
				"elementId": "ktaL-ST8nRNkOM2-21K2M",
				"gap": 15.519351204710858,
				"focus": -0.1084908848217952
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "tTtno8Ht",
			"type": "text",
			"x": -2012.1441434310284,
			"y": -677.5236224082226,
			"width": 40,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1096039152,
			"version": 3,
			"versionNonce": 81928432,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1701503449721,
			"link": null,
			"locked": false,
			"text": "步长",
			"rawText": "步长",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 18,
			"containerId": "IBDr7zQgfbI17gBLHVACR",
			"originalText": "步长",
			"lineHeight": 1.25
		},
		{
			"id": "aDGaBLryry3iq9nFtLpBw",
			"type": "image",
			"x": -1648.8950444907505,
			"y": -845.536382057545,
			"width": 343.44444444444434,
			"height": 300.75283446712007,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 891871248,
			"version": 167,
			"versionNonce": 1921109232,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "Z0hdrFck5Idt9KTjUbKUg",
					"type": "arrow"
				}
			],
			"updated": 1701503456918,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "a567db0057c371f3a83abd140f7e93d847942469",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "Z0hdrFck5Idt9KTjUbKUg",
			"type": "arrow",
			"x": -1893.2164730621794,
			"y": -555.9270588410789,
			"width": 226.25,
			"height": 86.25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 760109072,
			"version": 48,
			"versionNonce": 1771927280,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1701504063448,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					226.25,
					-86.25
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "uFXZRQSQS_UyARBTqV_Is",
				"gap": 19.86648570999398,
				"focus": 0.28346404657679164
			},
			"endBinding": {
				"elementId": "aDGaBLryry3iq9nFtLpBw",
				"gap": 18.071428571428896,
				"focus": 0.08973965433667218
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "0PG74kFMZIDBH6EElHYo1",
			"type": "image",
			"x": -2700.8106413590876,
			"y": -1589.0566781784048,
			"width": 914.4921794247871,
			"height": 473.7234262786059,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1023556848,
			"version": 333,
			"versionNonce": 499127536,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "2fEk8pTnmf5YD2psjiOgY",
					"type": "arrow"
				},
				{
					"id": "yTFJ2vwlXmq2tOLFbqPyQ",
					"type": "arrow"
				}
			],
			"updated": 1701504087779,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "b011aa504cd9ba7dfda05fc75ed0753ae359764c",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "2fEk8pTnmf5YD2psjiOgY",
			"type": "arrow",
			"x": -2484.5951936812653,
			"y": -940.5466774584308,
			"width": 187.99999999999955,
			"height": 161.33333333333326,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 307054320,
			"version": 43,
			"versionNonce": 738774032,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1701504079669,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					187.99999999999955,
					-161.33333333333326
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "W7u1JCQGn9PzH66mC0U_Z",
				"focus": -0.34846572027780903,
				"gap": 10.911943939098762
			},
			"endBinding": {
				"elementId": "0PG74kFMZIDBH6EElHYo1",
				"focus": -0.32547687488590715,
				"gap": 13.453241108034717
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "yTFJ2vwlXmq2tOLFbqPyQ",
			"type": "arrow",
			"x": -1969.928527014599,
			"y": -947.2133441250976,
			"width": 229.33333333333326,
			"height": 150.66666666666652,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1257604624,
			"version": 41,
			"versionNonce": 1708913392,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1701504087779,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-229.33333333333326,
					-150.66666666666652
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "ktaL-ST8nRNkOM2-21K2M",
				"focus": 0.5210889112120498,
				"gap": 13.345436557947494
			},
			"endBinding": {
				"elementId": "0PG74kFMZIDBH6EElHYo1",
				"focus": 0.41917950045508445,
				"gap": 17.453241108034717
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 2827.9285270145992,
		"scrollY": 1899.3800107917646,
		"zoom": {
			"value": 0.7500000000000001
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%