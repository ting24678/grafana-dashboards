# blackbox_exporter 黑盒 http 探针监控面板

## grafana 官方站点仪表板地址

- 中文版 : https://grafana.com/grafana/dashboards/16292
- English version : [https://grafana.com/grafana/dashboards/16293](https://grafana.com/grafana/dashboards/16293)

**仪表板 ID :** `16292`、`16293`

## 选择器说明
- project : 对应 target 的 project 标签
- app : 对应 target 的 app 标签

## v2 更新概要

- 新增 `证书剩余不足 30 天实例` 单独列出表格
- 增加 `非 https 协议` 的实例单元格配色
- 修复 `Fail` 在没有失败主机时显示 `No data` 问题
- 修复 `失败实例` 和 `实力状态占比` 受时间范围影响数据不准确问题
- 增加 `响应码变化记录` 图表，可对过去时间的响应码变化进行查看

# 界面预览

## 中文面板

![chinese1](PreviewImages/blackbox_exporter-http-Dashboards-chinese.png)

![chinese1](PreviewImages/blackbox_exporter-http-Dashboards-chinese2.png)

![chinese1](PreviewImages/blackbox_exporter-http-Dashboards-chinese3.png)

## English panel

![english1](PreviewImages/blackbox_exporter-http-Dashboards-english.png)

![english1](PreviewImages/blackbox_exporter-http-Dashboards-english2.png)

![english1](PreviewImages/blackbox_exporter-http-Dashboards-english3.png)

