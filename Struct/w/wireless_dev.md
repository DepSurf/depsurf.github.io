# Struct: <code>wireless_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool p2p_started;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    u32 owner_nlportid;
    struct (anon) wext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool p2p_started;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    u32 owner_nlportid;
    struct (anon) wext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    u32 owner_nlportid;
    struct (anon) wext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    bool registered;
    bool registering;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    bool registered;
    bool registering;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    bool registered;
    bool registering;
    u8[6] address;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    u8 connected;
    bool ps;
    int ps_timeout;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
    union (anon) u;
    struct (anon)[15] links;
    u16 valid_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    bool registered;
    bool registering;
    u8[6] address;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    u8 connected;
    bool ps;
    int ps_timeout;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
    union (anon) u;
    struct (anon)[15] links;
    u16 valid_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    u8 mgmt_registrations_need_update;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    bool registered;
    bool registering;
    u8[6] address;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    u8 connected;
    bool ps;
    int ps_timeout;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
    union (anon) u;
    struct (anon)[15] links;
    u16 valid_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    u8 mgmt_registrations_need_update;
    bool use_4addr;
    bool is_running;
    bool registered;
    bool registering;
    u8[6] address;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    u8 connected;
    bool ps;
    int ps_timeout;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct wiphy_work cqm_rssi_work;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
    long unsigned int unprot_beacon_reported;
    union (anon) u;
    struct (anon)[15] links;
    u16 valid_links;
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
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
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
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct wireless_dev {
    struct wiphy * wiphy;
    enum nl80211_iftype iftype;
    struct list_head list;
    struct net_device * netdev;
    u32 identifier;
    struct list_head mgmt_registrations;
    spinlock_t mgmt_registrations_lock;
    struct mutex mtx;
    bool use_4addr;
    bool is_running;
    u8[6] address;
    u8[32] ssid;
    u8 ssid_len;
    u8 mesh_id_len;
    u8 mesh_id_up_len;
    struct cfg80211_conn * conn;
    struct cfg80211_cached_keys * connect_keys;
    enum ieee80211_bss_type conn_bss_type;
    u32 conn_owner_nlportid;
    struct work_struct disconnect_wk;
    u8[6] disconnect_bssid;
    struct list_head event_list;
    spinlock_t event_lock;
    struct cfg80211_internal_bss * current_bss;
    struct cfg80211_chan_def preset_chandef;
    struct cfg80211_chan_def chandef;
    bool ibss_fixed;
    bool ibss_dfs_possible;
    bool ps;
    int ps_timeout;
    int beacon_interval;
    u32 ap_unexpected_nlportid;
    u32 owner_nlportid;
    bool nl_owner_dead;
    bool cac_started;
    long unsigned int cac_start_time;
    unsigned int cac_time_ms;
    struct (anon) wext;
    struct cfg80211_cqm_config * cqm_config;
    struct list_head pmsr_list;
    spinlock_t pmsr_lock;
    struct work_struct pmsr_free_wk;
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
<code>enum ieee80211_bss_type conn_bss_type</code>
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
<code>bool is_running</code>
</li>
<li>
<b>Field removed. </b>
<code>bool p2p_started</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 conn_owner_nlportid</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct disconnect_wk</code>
</li>
<li>
<b>Field added. </b>
<code>u8[6] disconnect_bssid</code>
</li>
<li>
<b>Field added. </b>
<code>bool nl_owner_dead</code>
</li>
<li>
<b>Field added. </b>
<code>struct cfg80211_cqm_config * cqm_config</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head pmsr_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t pmsr_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct pmsr_free_wk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 mgmt_registrations_need_update</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int unprot_beacon_reported</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool registered</code>
</li>
<li>
<b>Field added. </b>
<code>bool registering</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>spinlock_t mgmt_registrations_lock</code>
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
<code>u8 connected</code>
</li>
<li>
<b>Field added. </b>
<code>union (anon) u</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon)[15] links</code>
</li>
<li>
<b>Field added. </b>
<code>u16 valid_links</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[32] ssid</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 ssid_len</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 mesh_id_len</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 mesh_id_up_len</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cfg80211_internal_bss * current_bss</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cfg80211_chan_def preset_chandef</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cfg80211_chan_def chandef</code>
</li>
<li>
<b>Field removed. </b>
<code>bool ibss_fixed</code>
</li>
<li>
<b>Field removed. </b>
<code>bool ibss_dfs_possible</code>
</li>
<li>
<b>Field removed. </b>
<code>int beacon_interval</code>
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
<code>struct wiphy_work cqm_rssi_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex mtx</code>
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
