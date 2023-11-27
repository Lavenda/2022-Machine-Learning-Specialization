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
			"version": 532,
			"versionNonce": 329039951,
			"isDeleted": false,
			"id": "RCtE_NuJ-3fCUi0ViQC96",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -773.8941103155232,
			"y": -287.9347618061405,
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
			"updated": 1701064528592,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 815,
			"versionNonce": 298414113,
			"isDeleted": false,
			"id": "V98MtTA7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -760.1507097417928,
			"y": -273.1014335590702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.1798858642578,
			"height": 25,
			"seed": 1687475157,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528592,
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
			"version": 709,
			"versionNonce": 1574821487,
			"isDeleted": false,
			"id": "iI0EUlEuFOB1EEspp-R5M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -164.11152528447985,
			"y": -565.6934685228722,
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
			"updated": 1701064528592,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 564,
			"versionNonce": 1581827073,
			"isDeleted": false,
			"id": "2jxO2BT9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -91.36352042764958,
			"y": -559.5014335590702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.61988830566406,
			"height": 50,
			"seed": 918966587,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528592,
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
			"version": 784,
			"versionNonce": 446052495,
			"isDeleted": false,
			"id": "IvWsf1nJ5GO4onCOp4yBn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -657.1718802444993,
			"y": -288.9347618061405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 160.94445694069486,
			"height": 142.58600738583596,
			"seed": 1766007419,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701064528593,
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
					111.94445694069486,
					-141.6666717529297
				],
				[
					160.94445694069486,
					-142.58600738583596
				]
			]
		},
		{
			"type": "rectangle",
			"version": 858,
			"versionNonce": 728931297,
			"isDeleted": false,
			"id": "tIXqoYt7pIyyf6cif5KJS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -164.11152528447985,
			"y": -376.7934685228722,
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
			"updated": 1701064528593,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 744,
			"versionNonce": 1870548655,
			"isDeleted": false,
			"id": "R2FXwGlk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -107.71351127237614,
			"y": -370.6014335590702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.3198699951172,
			"height": 50,
			"seed": 507601755,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 196,
			"versionNonce": 156661697,
			"isDeleted": false,
			"id": "FBwUP0Lf1hh3VU2K3LgDV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -321.65729882506116,
			"y": -465.9934685228722,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 156.5457735405813,
			"height": 66.2273006691043,
			"seed": 2016169211,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701064528593,
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
					107.54577354058131,
					-65.30796503619797
				],
				[
					156.5457735405813,
					-66.2273006691043
				]
			]
		},
		{
			"type": "arrow",
			"version": 236,
			"versionNonce": 926851279,
			"isDeleted": false,
			"id": "QjReOLRGhKsCQEPZ2f5cq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -313.8613906678434,
			"y": -401.60939859526815,
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
			"updated": 1701064528593,
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
			"version": 641,
			"versionNonce": 1511249825,
			"isDeleted": false,
			"id": "B0DXYnz5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 167.00437273484476,
			"y": -622.0014335590702,
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
			"updated": 1701064528593,
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
			"version": 555,
			"versionNonce": 1668263663,
			"isDeleted": false,
			"id": "VXQ2ORUv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 167.00437273484476,
			"y": -420.6014335590702,
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
			"updated": 1701064528593,
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
			"version": 118,
			"versionNonce": 265960321,
			"isDeleted": false,
			"id": "8tRqsb0R10cKeAZK5pQK_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 78.00437273484478,
			"y": -534.5014335590702,
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
			"updated": 1701064528593,
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
			"version": 144,
			"versionNonce": 513407247,
			"isDeleted": false,
			"id": "z1gryULx8-yDPQZIZfcXC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 78.00437273484478,
			"y": -345.6014335590702,
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
			"updated": 1701064528593,
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
			"version": 684,
			"versionNonce": 719922017,
			"isDeleted": false,
			"id": "fKij4jTMEcxLa_lhhahXr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -495.22742330380447,
			"y": -464.9934685228722,
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
			"updated": 1701064528593,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 572,
			"versionNonce": 775290671,
			"isDeleted": false,
			"id": "dLE3qzpK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -470.09938304658357,
			"y": -458.8014335590702,
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
			"updated": 1701064528593,
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
			"version": 1050,
			"versionNonce": 2005929793,
			"isDeleted": false,
			"id": "aL7a3S2Z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -496.052153916178,
			"y": -520.8759451637351,
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
			"updated": 1701064528593,
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
			"version": 277,
			"versionNonce": 346833231,
			"isDeleted": false,
			"id": "u_CfVIZ9DPqfP4w1YyReM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -658.9871953714046,
			"y": -232.26810531199988,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 162.75977206760012,
			"height": 157.58600738583598,
			"seed": 1952676026,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701064528593,
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
					113.75977206760012,
					156.6666717529297
				],
				[
					162.75977206760012,
					157.58600738583598
				]
			]
		},
		{
			"type": "rectangle",
			"version": 895,
			"versionNonce": 204373793,
			"isDeleted": false,
			"id": "2KxooE3CHe0xd4hRHrYCF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -495.22742330380447,
			"y": -103.59346852287223,
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
			"updated": 1701064528593,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 784,
			"versionNonce": 1934966639,
			"isDeleted": false,
			"id": "FyMqHPYU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -480.44937389131013,
			"y": -97.4014335590702,
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
			"updated": 1701064528593,
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
			"version": 249,
			"versionNonce": 120845057,
			"isDeleted": false,
			"id": "ObcZHlEV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -494.2057886804955,
			"y": -27.41393216768722,
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
			"updated": 1701064528593,
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
			"version": 836,
			"versionNonce": 746158479,
			"isDeleted": false,
			"id": "ENtDubxVlEDWTv55VJ8f5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -164.11152528447985,
			"y": -201.79346852287222,
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
			"updated": 1701064528593,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 712,
			"versionNonce": 220195553,
			"isDeleted": false,
			"id": "5TS7ggQw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -89.60352592081364,
			"y": -195.6014335590702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.09989929199219,
			"height": 50,
			"seed": 1591336570,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 167,
			"versionNonce": 1162964911,
			"isDeleted": false,
			"id": "tXCND7LUCXN2-21mFnNBy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -320.2622415758749,
			"y": -104.59346852287223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.15071629139504,
			"height": 63.72730066910427,
			"seed": 1204959078,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701064528593,
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
					106.15071629139504,
					-62.80796503619797
				],
				[
					155.15071629139504,
					-63.72730066910427
				]
			]
		},
		{
			"type": "rectangle",
			"version": 891,
			"versionNonce": 109176513,
			"isDeleted": false,
			"id": "ANMgnInMCHc2epvuIuBbx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -164.11152528447985,
			"y": -102.4014335590702,
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
			"updated": 1701064528593,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 845,
			"versionNonce": 134586831,
			"isDeleted": false,
			"id": "Bpt7t9kU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.99350242227848,
			"y": -97.4014335590702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 174.87985229492188,
			"height": 50,
			"seed": 590538150,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 460,
			"versionNonce": 502884001,
			"isDeleted": false,
			"id": "X3SP5xPy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 167.00437273484476,
			"y": -233.1014335590702,
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
			"updated": 1701064528593,
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
			"version": 168,
			"versionNonce": 1705938927,
			"isDeleted": false,
			"id": "AB9ftzFa6xfLXn6_cdH_F",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -253.11152528447985,
			"y": -72.4014335590702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87.99999999999997,
			"height": 0,
			"seed": 421870138,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701064528593,
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
					39,
					0
				],
				[
					87.99999999999997,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 111,
			"versionNonce": 2117462657,
			"isDeleted": false,
			"id": "w6mr3Zc2zsOmNZfBj7QyV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 78.00437273484478,
			"y": -170.6014335590702,
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
			"updated": 1701064528593,
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
			"version": 34,
			"versionNonce": 408205839,
			"isDeleted": false,
			"id": "75pAKB5C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 167.00437273484476,
			"y": -84.9014335590702,
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
			"updated": 1701064528593,
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
			"version": 1025,
			"versionNonce": 1341583969,
			"isDeleted": false,
			"id": "WYn84jodtcLPr-DFttTRA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -161.24269903614623,
			"y": -16.90652817455225,
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
			"updated": 1701064528593,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1061,
			"versionNonce": 82878511,
			"isDeleted": false,
			"id": "2mFctrNh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -156.01463741662064,
			"y": -11.90652817455225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 230.65977478027344,
			"height": 50,
			"seed": 2014837143,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 142,
			"versionNonce": 2014051905,
			"isDeleted": false,
			"id": "rBJjOVns",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 182.7829335162977,
			"y": -5.144246333691854,
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
			"updated": 1701064528593,
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
			"version": 131,
			"versionNonce": 1567277647,
			"isDeleted": false,
			"id": "0hnN2M0kQREy0ukP2o2rn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 78.00437273484476,
			"y": -72.4014335590702,
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
			"updated": 1701064528593,
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
			"version": 385,
			"versionNonce": 357862945,
			"isDeleted": false,
			"id": "1I5SLB_pwJ6LN-cNK43uJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 83.02482687723767,
			"y": 10.163450924294027,
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
			"updated": 1701064528593,
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
			"version": 346,
			"versionNonce": 43753583,
			"isDeleted": false,
			"id": "qkWQWMP5DfTnCf2NM4eUY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -259.8097607778001,
			"y": -40.20939859526816,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.56706174165384,
			"height": 24.919262200131303,
			"seed": 240471767,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1701064528593,
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
					45.698235493320226,
					12.807965036197963
				],
				[
					97.56706174165384,
					24.919262200131303
				]
			]
		},
		{
			"type": "text",
			"version": 268,
			"versionNonce": 1052779009,
			"isDeleted": false,
			"id": "LqRXJMJO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -730.8341197521459,
			"y": 264.44238506546606,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 909.6193237304688,
			"height": 50,
			"seed": 1247864379,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 563,
			"versionNonce": 642497167,
			"isDeleted": false,
			"id": "WwMoVUVy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -693.5633753699415,
			"y": 1178.3356321981485,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 916.2596435546875,
			"height": 75,
			"seed": 246236265,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 463,
			"versionNonce": 21903841,
			"isDeleted": false,
			"id": "hwbVWO9k",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -471.6087447379591,
			"y": 1146.2868546865086,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 738.8593139648438,
			"height": 50,
			"seed": 1341371143,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 85,
			"versionNonce": 758354095,
			"isDeleted": false,
			"id": "mW8uERUI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -755.5353803829007,
			"y": -645.2584255125248,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 303.4197692871094,
			"height": 25,
			"seed": 1756866793,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 237,
			"versionNonce": 504255937,
			"isDeleted": false,
			"id": "XvUB6fTvVYKr9-Uljbnnz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -687.485001627024,
			"y": 1272.9821759912325,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1263.5634028892448,
			"height": 624.7619047619044,
			"seed": 571944743,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 18,
			"versionNonce": 1358668495,
			"isDeleted": false,
			"id": "u0pu0q5h",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -669.5962924670307,
			"y": 2059.246763742663,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 160.37986755371094,
			"height": 25,
			"seed": 1912570407,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 874,
			"versionNonce": 136312225,
			"isDeleted": false,
			"id": "NUGCTc8u",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -665.173202792535,
			"y": 2094.0045848620994,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 741.5997314453125,
			"height": 150,
			"seed": 1129281865,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 890,
			"versionNonce": 37515503,
			"isDeleted": false,
			"id": "IqAnivRDaYjbJJu4Q2hPY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -662.7232122271632,
			"y": 2209.9340329532697,
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
			"updated": 1701064528593,
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
			"version": 700,
			"versionNonce": 582130049,
			"isDeleted": false,
			"id": "gtjX9QWv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -646.8151679262161,
			"y": 2315.3087457096167,
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
			"updated": 1701064528593,
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
			"version": 629,
			"versionNonce": 176061199,
			"isDeleted": false,
			"id": "BYguYNIMOezIEv6NNP7Ln",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -669.0413640895042,
			"y": 2771.1178747328972,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 856.7527027971033,
			"height": 433.85430985633366,
			"seed": 1102322439,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 290,
			"versionNonce": 1057341793,
			"isDeleted": false,
			"id": "roCdQqPcCMVo_LYmfZSO5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 118.36472600582263,
			"y": 2080.534446166747,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 472.3964904726373,
			"height": 218.675036934397,
			"seed": 1246800999,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 172,
			"versionNonce": 1849311535,
			"isDeleted": false,
			"id": "0CkyQn0K",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -663.3058372578017,
			"y": 2670.999389257052,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 583.2198486328125,
			"height": 75,
			"seed": 1993151337,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 242,
			"versionNonce": 1516825921,
			"isDeleted": false,
			"id": "m86LMwqL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -650.2287611638551,
			"y": 3271.4551332374153,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 743.83984375,
			"height": 25,
			"seed": 270360903,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 341,
			"versionNonce": 249054031,
			"isDeleted": false,
			"id": "aqnen8nFKyo2gpg1EpPtu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -697.8346723558798,
			"y": 3303.058067131119,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1064.0052096772322,
			"height": 593.844934462181,
			"seed": 1801913897,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 40,
			"versionNonce": 473668897,
			"isDeleted": false,
			"id": "iRYKytWy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -672.0238879870986,
			"y": 4040.8231100979174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 200.0198516845703,
			"height": 25,
			"seed": 1868944489,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 448,
			"versionNonce": 212926831,
			"isDeleted": false,
			"id": "k6pCMJi9bfsYnlcU_-Sn1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 91.97663843748182,
			"y": 4115.902257633246,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 676.8346557827581,
			"height": 368.96889221490636,
			"seed": 1773560393,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 817,
			"versionNonce": 334319873,
			"isDeleted": false,
			"id": "cZWstGyR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -661.8085931374435,
			"y": 4081.59081630599,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 655.760009765625,
			"height": 250,
			"seed": 641048873,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 733,
			"versionNonce": 1762458511,
			"isDeleted": false,
			"id": "F2q0HB3N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -657.3500448088633,
			"y": 4358.2044090205245,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 670.6998291015625,
			"height": 200,
			"seed": 1382503335,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 402,
			"versionNonce": 922585313,
			"isDeleted": false,
			"id": "prOUEkIID5vLxziEwEVmt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -669.5285918975017,
			"y": 4547.0162546317415,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 995.1131383841143,
			"height": 494.1013152393345,
			"seed": 1488723815,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 94,
			"versionNonce": 1747235247,
			"isDeleted": false,
			"id": "WLQ1pSxgoqzTlBdIs63j4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -732.5414080476423,
			"y": 336.55159598879936,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1397.7298364354206,
			"height": 674.3333333333335,
			"seed": 1914650247,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 643,
			"versionNonce": 519816385,
			"isDeleted": false,
			"id": "dUbkEhbc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -654.6424298328745,
			"y": 5159.944629855515,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 738.0999755859375,
			"height": 25,
			"seed": 582901066,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 234,
			"versionNonce": 857777103,
			"isDeleted": false,
			"id": "WU6I4DFWr0Zed8labLMHe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -601.5156664009007,
			"y": 5198.7641304678455,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 846.6310906763134,
			"height": 451.1803197382337,
			"seed": 368987082,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"version": 290,
			"versionNonce": 126321825,
			"isDeleted": false,
			"id": "CSlMJxyv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -572.6116421607338,
			"y": 5651.187283905032,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 210.4263916015625,
			"height": 47.785850757519526,
			"seed": 1026758102,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1701064528593,
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
			"id": "HvJSKflL",
			"type": "text",
			"x": -649.8747413809762,
			"y": 5115.990118512462,
			"width": 142.27987670898438,
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
			"seed": 144139361,
			"version": 51,
			"versionNonce": 974737903,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1701064528593,
			"link": null,
			"locked": false,
			"text": "## Derivative",
			"rawText": "## Derivative",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 18,
			"containerId": null,
			"originalText": "## Derivative",
			"lineHeight": 1.25
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
		"scrollX": 973.7499498611146,
		"scrollY": -4606.97444255755,
		"zoom": {
			"value": 1.2226789344147546
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