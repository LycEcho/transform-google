## 谷歌翻译-api
### 谷歌翻译api 更新时间: 2023/09/15

## 接口介绍。
### 根据词性和语义分析 去掉多余的词 留下有用的关键词

## 在线体验效果
### http://ai.lycecho.com/participle

## 联系方式

## 接口地址 http://ai.lycecho.com/api/getTransform

## post方式 json格式发送过来 如果想用form方式 用这个链接
### http://ai.lycecho.com/api/getTransform/form

## 举例
{"content":"测试","from":"zh-CN","to":"en","token":"getTransform"}
## 参数

| 名称	| 类型	| 必填	| 说明 |
| :------------: | :------------: | :------------: | :------------: |
| content	| string	| 是	| 文章内容
| from	| string	| 是	| 翻译前语言      
| to	| string	| 是	| 要翻译成什么语言
| token	| string	| 是	| 接口密钥可在购买接口后获取


## from 和 to的值 
【zh-CN=中文（简体）】<br>
【zh-TW=中文（繁体）】<br>
【ru=俄语】<br>
【en=英语】<br>
【de=德语】<br>
【ko=韩语】<br>
【fr=法语】<br>
【ja=日语】<br>
【支持所有语言，可联系客服获取】

### 如果有帮助到您，欢迎给我个star，谢谢！

| 功能说明             | 付费版本 | 免费版本 |
| -------------------- | -------- | -------- |
| 价格                 | 100元/月  | 免费     |
| JSON接口             | √        | √        |
| QPS并发              | 不限     | 1并发    |
| 日请求次数           | 不限    | 共享10W      |
| IP白名单             | √        | ×        |
| 技术支持(简单)       | √        | ×        |
| 微信咨询(kekegov) | √        | √        |
