# Struct: <code>mptcp_pernet</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    int mptcp_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    int mptcp_enabled;
    unsigned int add_addr_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    int mptcp_enabled;
    unsigned int add_addr_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    unsigned int add_addr_timeout;
    unsigned int stale_loss_cnt;
    u8 mptcp_enabled;
    u8 checksum_enabled;
    u8 allow_join_initial_addr_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    unsigned int add_addr_timeout;
    unsigned int stale_loss_cnt;
    u8 mptcp_enabled;
    u8 checksum_enabled;
    u8 allow_join_initial_addr_port;
    u8 pm_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    unsigned int add_addr_timeout;
    unsigned int stale_loss_cnt;
    u8 mptcp_enabled;
    u8 checksum_enabled;
    u8 allow_join_initial_addr_port;
    u8 pm_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    unsigned int add_addr_timeout;
    unsigned int stale_loss_cnt;
    u8 mptcp_enabled;
    u8 checksum_enabled;
    u8 allow_join_initial_addr_port;
    u8 pm_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    unsigned int add_addr_timeout;
    unsigned int close_timeout;
    unsigned int stale_loss_cnt;
    u8 mptcp_enabled;
    u8 checksum_enabled;
    u8 allow_join_initial_addr_port;
    u8 pm_type;
    char[16] scheduler;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct mptcp_pernet {
    struct ctl_table_header * ctl_table_hdr;
    int mptcp_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int add_addr_timeout</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int stale_loss_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>u8 checksum_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>u8 allow_join_initial_addr_port</code>
</li>
<li>
<b>Field type changed. </b>
<code>int mptcp_enabled</code> ➡️ <code>u8 mptcp_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 pm_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int close_timeout</code>
</li>
<li>
<b>Field added. </b>
<code>char[16] scheduler</code>
</li>
</ul>
</details>
</li>
</ul>
