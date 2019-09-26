# App设置

> 更新记录

<table>
    <tr>
        <th style="width:250px;">日期</th>
        <th>更新内容</th>
    </tr>
    <tr>
        <td>2018-06-04 10:53:38</td>
        <td>生成时间</td>
    </tr>
</table>

> 字段

<table>
    <tr>
        <th style="width:500px;">名称</th>
        <th style="width:300px;">路径</th>
        <th style="width:100px;">类型</th>
        <th>可选值</th>
    </tr>
    <tr>
        <td>积分模块开关</td>
        <td>module.score.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>积分模块: 消费1元积分数</td>
        <td>module.score.inUnit</td>
        <td>int</td>
        <td>消费1元积分数, 默认: 1</td>
    </tr>
    <tr>
        <td>积分模块: 抵扣1元金额所需积分数</td>
        <td>module.score.outUnit</td>
        <td>int</td>
        <td>抵扣1元金额所需积分数</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>预储值模块开关</td>
        <td>module.deposit.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>服务卡模块开关</td>
        <td>module.serviceCard.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>微信模块开关</td>
        <td>module.wechat.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>短信模块开关</td>
        <td>module.sms.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>通知模块开关</td>
        <td>module.notice.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 验光单通知开关</td>
        <td>module.notice.optometry.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 验光单通知方式</td>
        <td>module.notice.optometry.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 下单通知开关</td>
        <td>module.notice.orderCreate.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 下单通知方式</td>
        <td>module.notice.orderCreate.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 储值卡使用通知开关</td>
        <td>module.notice.depositUse.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 储值卡使用通知方式</td>
        <td>module.notice.depositUse.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 积分使用通知开关</td>
        <td>module.notice.scoreUse.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 积分使用通知方式</td>
        <td>module.notice.scoreUse.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 服务卡使用通知开关</td>
        <td>module.notice.serviceCardUse.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 服务卡使用通知方式</td>
        <td>module.notice.serviceCardUse.enabled</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 取货通知开关</td>
        <td>module.notice.orderReady.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 取货通知方式</td>
        <td>module.notice.orderReady.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 订单完成通知开关</td>
        <td>module.notice.orderComplete.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 订单完成通知方式</td>
        <td>module.notice.orderComplete.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 验光筛查通知开关</td>
        <td>module.notice.optometryReview.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 验光筛查通知方式</td>
        <td>module.notice.optometryReview.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 框架换镜通知开关</td>
        <td>module.notice.glassExpired.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 框架换镜通知方式</td>
        <td>module.notice.glassExpired.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>通知模块: 隐形换镜通知开关</td>
        <td>module.notice.contactLensExpired.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>通知模块: 隐形换镜通知方式</td>
        <td>module.notice.contactLensExpired.method</td>
        <td>array</td>
        <td>可选值: wechat: 微信, sms: 短信</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>会员等级模块开关</td>
        <td>module.level.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>会员等级</td>
        <td>module.level.list</td>
        <td>array</td>
        <td>按消费金额: 范例: [{"level":1, "name":"普通会员", "money":0, "benefit": "每年享受一次免费眼健康全面检查服务"}, {"level":2, "name":"铜牌会员", "money":500, "benefit": "每年享受两次免费眼健康全面检查服务"}]</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>顾客画像模块开关</td>
        <td>module.tag.enabled</td>
        <td>int</td>
        <td>1:是 0否</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>验光模块记录法</td>
        <td>module.optometry.standard</td>
        <td>int</td>
        <td>0: 五分记录法 1: 小数记录法</td>
    </tr>
</table>


## 获取APP设置

```
GET /core/v1/app-setting/view
```

> 请求参数: path: 路径

> 设置项采用JsonPath库解析, 使用方式: https://github.com/json-path/JsonPath, 注: path参数已经前置了$.字符
