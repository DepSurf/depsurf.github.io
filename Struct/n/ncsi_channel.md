# Struct: <code>ncsi_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_filter *[4] filters;
    struct ncsi_channel_stats stats;
    struct timer_list timer;
    bool enabled;
    unsigned int timeout;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_filter *[4] filters;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_filter *[4] filters;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_filter *[4] filters;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
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
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
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
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    bool reconfigure_needed;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_mac_filter mac_filter;
    struct ncsi_channel_vlan_filter vlan_filter;
    struct ncsi_channel_stats stats;
    struct (anon) monitor;
    struct list_head node;
    struct list_head link;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct ncsi_channel {
    unsigned char id;
    int state;
    spinlock_t lock;
    struct ncsi_package * package;
    struct ncsi_channel_version version;
    struct ncsi_channel_cap[6] caps;
    struct ncsi_channel_mode[8] modes;
    struct ncsi_channel_filter *[4] filters;
    struct ncsi_channel_stats stats;
    struct timer_list timer;
    bool enabled;
    unsigned int timeout;
    struct list_head node;
    struct list_head link;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) monitor</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list timer</code>
</li>
<li>
<b>Field removed. </b>
<code>bool enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int timeout</code>
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
<b>Field added. </b>
<code>bool reconfigure_needed</code>
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
<code>struct ncsi_channel_mac_filter mac_filter</code>
</li>
<li>
<b>Field added. </b>
<code>struct ncsi_channel_vlan_filter vlan_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ncsi_channel_filter *[4] filters</code>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
