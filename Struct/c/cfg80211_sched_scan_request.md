# Struct: <code>cfg80211_sched_scan_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    struct callback_head callback_head;
    u32 owner_nlportid;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    struct callback_head callback_head;
    u32 owner_nlportid;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    struct callback_head callback_head;
    u32 owner_nlportid;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
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
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
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
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cfg80211_sched_scan_request {
    u64 reqid;
    struct cfg80211_ssid * ssids;
    int n_ssids;
    u32 n_channels;
    enum nl80211_bss_scan_width scan_width;
    const u8 * ie;
    size_t ie_len;
    u32 flags;
    struct cfg80211_match_set * match_sets;
    int n_match_sets;
    s32 min_rssi_thold;
    u32 delay;
    struct cfg80211_sched_scan_plan * scan_plans;
    int n_scan_plans;
    u8[6] mac_addr;
    u8[6] mac_addr_mask;
    bool relative_rssi_set;
    s8 relative_rssi;
    struct cfg80211_bss_select_adjust rssi_adjust;
    struct wiphy * wiphy;
    struct net_device * dev;
    long unsigned int scan_start;
    bool report_results;
    struct callback_head callback_head;
    u32 owner_nlportid;
    bool nl_owner_dead;
    struct list_head list;
    struct ieee80211_channel *[0] channels;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 reqid</code>
</li>
<li>
<b>Field added. </b>
<code>bool relative_rssi_set</code>
</li>
<li>
<b>Field added. </b>
<code>s8 relative_rssi</code>
</li>
<li>
<b>Field added. </b>
<code>struct cfg80211_bss_select_adjust rssi_adjust</code>
</li>
<li>
<b>Field added. </b>
<code>bool report_results</code>
</li>
<li>
<b>Field added. </b>
<code>bool nl_owner_dead</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>enum nl80211_bss_scan_width scan_width</code>
</li>
</ul>
</details>
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
