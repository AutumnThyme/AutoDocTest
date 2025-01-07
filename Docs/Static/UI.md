# UI
## Fields
|Field|Type|Readonly|Description|
|---|---|---|---|
|TopCenter|String|False||
|TopLeft|String|False||
|TopRight|String|False||
|MiddleCenter|String|False||
|MiddleLeft|String|False||
|MiddleRight|String|False||
|BottomCenter|String|False||
|BottomLeft|String|False||
|BottomRight|String|False||
## Methods
|Function|Returns|Description|
|---|---|---|
|SetLabel(label : String, message : String)|Void||
|SetLabelForTime(label : String, message : String, time : Single)|Void||
|SetLabelAll(label : String, message : String)|Void||
|SetLabelForTimeAll(label : String, message : String, time : Single)|Void||
|CreatePopup(popupName : String, title : String, width : Int32, height : Int32)|String||
|ShowPopup(popupName : String)|Void||
|HidePopup(popupName : String)|Void||
|ClearPopup(popupName : String)|Void||
|AddPopupLabel(popupName : String, label : String)|Void||
|AddPopupButton(popupName : String, label : String, callback : String)|Void||
|AddPopupBottomButton(popupName : String, label : String, callback : String)|Void||
|AddPopupButtons(popupName : String, labels : CustomLogicListBuiltin, callbacks : CustomLogicListBuiltin)|Void||
|WrapStyleTag(text : String, style : String, arg : String = )|String||
|GetLocale(cat : String, sub : String, key : String)|String||
|GetLanguage()|String||
|ShowChangeCharacterMenu()|Void||
|SetScoreboardHeader(header : String)|Void||
|SetScoreboardProperty(property : String)|Void||
|GetThemeColor(panel : String, category : String, item : String)|CustomLogicColorBuiltin||
