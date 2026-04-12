# 免责说明

我会突然夹带私活，不要使用我的规则源，出事需要自身负责，我不保真。

## 统计信息

- **原始条目数**：164
- **去重后域名数**：100
- **重复条目数**：64
- **最后更新**：2026-04-13 06:23:41（北京时间）

## 路由表文件（CIDR 格式）

- **IPv4 中国全量:**`https://raw.githubusercontent.com/jasonandy888/ad/main/xiaosizi.txt`
- **IPv6 中国全量:**`https://raw.githubusercontent.com/jasonandy888/ad/main/xiaosizi_ipv6.txt`
- **最后更新时间:** {{TIMESTAMP}}
### 📈 总体统计"
- **IPv4 合并去重后总数:** {{xiaosizi_count}}
- **IPv6 合并去重后总数:** {{xiaosizi6_count}}

**可用于路由器、防火墙、分流软件等。每日更新。**

## 生成的文件

- `hosts.txt` – 标准 hosts 格式，指向 `0.0.0.0`
- `domains.txt` – 纯域名列表，每行一个域名
- `adguardhome.txt` – AdGuard Home 规则格式，`||domain^`

## 使用说明

- **hosts**：将 `hosts.txt` 内容添加到系统 `/etc/hosts` 或路由器 DNS 屏蔽列表中。
- **AdGuard Home**：在“DNS 拦截列表”中添加 `adguardhome.txt` 的 URL。
- **纯域名**：可用于其他支持域名列表的 DNS 工具。
