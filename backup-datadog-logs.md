# Backup Datadog logs

需求

* 因为 Datadog 只保存 30 天 log，所以需要备份。
* 因为客户可能需要查看某个月的 log，所以当客户需要时应该提供一个可下载的 zip。

前提

* 一个 Datadog account 中含有多个客户的 log，他们使用 host 进行区分。
* 使用 Azure Cloud

功能概要

# 将 log 从 Datadog 备份到 Azure Storage 中
# 以 host 和 day 分别存储 log
# 当客户请求某个月的 log 时，提供可下载的 zip
# log 要求时按时间顺序排序，并且无重复

要求：

* 使用 TypeScript / Java 实现
* 编写适当的 Testing
* 提供 README 和 DEOM
* 代码提交至本仓库
