# Struct: <code>netns_nf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct list_head[104] hooks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct list_head[104] hooks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entry *[104] hooks;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entry *[104] hooks;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[104] hooks;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    unsigned int defrag_ipv4_users;
    unsigned int defrag_ipv6_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    unsigned int defrag_ipv4_users;
    unsigned int defrag_ipv6_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_logger *[11] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    unsigned int defrag_ipv4_users;
    unsigned int defrag_ipv6_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_logger *[11] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    unsigned int defrag_ipv4_users;
    unsigned int defrag_ipv6_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_logger *[11] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    unsigned int defrag_ipv4_users;
    unsigned int defrag_ipv6_users;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netns_nf {
    struct proc_dir_entry * proc_netfilter;
    const struct nf_queue_handler * queue_handler;
    const struct nf_logger *[13] nf_loggers;
    struct ctl_table_header * nf_log_dir_header;
    struct nf_hook_entries *[5] hooks_ipv4;
    struct nf_hook_entries *[5] hooks_ipv6;
    struct nf_hook_entries *[3] hooks_arp;
    struct nf_hook_entries *[5] hooks_bridge;
    struct nf_hook_entries *[7] hooks_decnet;
    bool defrag_ipv4;
    bool defrag_ipv6;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct nf_queue_handler * queue_handler</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool defrag_ipv4</code>
</li>
<li>
<b>Field added. </b>
<code>bool defrag_ipv6</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[104] hooks</code> ➡️ <code>struct nf_hook_entry *[104] hooks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct nf_hook_entry *[104] hooks</code> ➡️ <code>struct nf_hook_entries *[104] hooks</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct nf_hook_entries *[5] hooks_ipv4</code>
</li>
<li>
<b>Field added. </b>
<code>struct nf_hook_entries *[5] hooks_ipv6</code>
</li>
<li>
<b>Field added. </b>
<code>struct nf_hook_entries *[3] hooks_arp</code>
</li>
<li>
<b>Field added. </b>
<code>struct nf_hook_entries *[5] hooks_bridge</code>
</li>
<li>
<b>Field added. </b>
<code>struct nf_hook_entries *[7] hooks_decnet</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nf_hook_entries *[104] hooks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool defrag_ipv4</code>
</li>
<li>
<b>Field removed. </b>
<code>bool defrag_ipv6</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int defrag_ipv4_users</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int defrag_ipv6_users</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct nf_queue_handler * queue_handler</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct nf_hook_entries *[7] hooks_decnet</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct nf_logger *[13] nf_loggers</code> ➡️ <code>const struct nf_logger *[11] nf_loggers</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
