### 关于查找
strings and should not contain U+0000 (nil byte) and U+10FFFF

https://unicode-table.com/cn/sets/special-symbols/







errString   qhUtil.ReturnErrString( "This wallet isn't exists: " ,walletName)


	QHType        string `json:"objectType"`
	Trad1eNo       string  `json:"tradeNo"`                //流水
	FromAddress        string `json:"fromAddress"`       //用户  FromAddress
	ToAddress        string `json:"fromAddress"`       //用户    ToAddress
	AssetCode     string `json:"assetCode"`          //资产code
	TradeType        string `json:"tradeType"`       //1.创建  2.增加 3.使用 4.转赠
	OldAmount       string  `json:"oldAmount"`       //交易之前 数量
	Amount       string  `json:"Amount"`             //交易数量
	NewAmount       string  `json:"NewAmount"`       //交易后数量
	Body          string `json:"body"`              //附加信息
	CreateTime    string `json:"createTime"`        //时间



asset 

	QHType        string `json:"objectType"`
	QHCode        string `json:"qhcode"`       //用户code
	AssetCode     string `json:"assetCode"`    //资产code
	Amount        string `json:"amount"`       //数量
	Body          string `json:"body"`        //附加信息
	CreateTime    string `json:"createTime"`
	UpdateTime    string `json:"updateTime"`
