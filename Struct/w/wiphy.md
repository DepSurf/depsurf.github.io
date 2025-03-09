# Struct: <code>wiphy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[1] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[1] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[2] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u64 cookie_counter;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[3] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u64 cookie_counter;
    u8 nan_supported_bands;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[3] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u64 cookie_counter;
    u8 nan_supported_bands;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[4] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u64 cookie_counter;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[3] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[7] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[7] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[5] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    struct mutex mtx;
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[8] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[5] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    struct mutex mtx;
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[8] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[5] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    struct rfkill * rfkill;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    struct mutex mtx;
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[8] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[6] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    struct rfkill * rfkill;
    u8 mbssid_max_interfaces;
    u8 ema_max_profile_periodicity;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    struct mutex mtx;
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[8] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[6] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    struct rfkill * rfkill;
    u8 mbssid_max_interfaces;
    u8 ema_max_profile_periodicity;
    u16 max_num_akm_suites;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    struct mutex mtx;
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[9] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[6] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    struct rfkill * rfkill;
    u8 mbssid_max_interfaces;
    u8 ema_max_profile_periodicity;
    u16 max_num_akm_suites;
    u16 hw_timestamp_max_peers;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct wiphy {
    struct mutex mtx;
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[9] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    const struct wiphy_iftype_akm_suites * iftype_akm_suites;
    unsigned int num_iftype_akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[6] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    long unsigned int tx_queue_len;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    struct (anon) tid_config_support;
    u8 max_data_retry_count;
    const struct cfg80211_sar_capa * sar_capa;
    struct rfkill * rfkill;
    u8 mbssid_max_interfaces;
    u8 ema_max_profile_periodicity;
    u16 max_num_akm_suites;
    u16 hw_timestamp_max_peers;
    char[0] priv;
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
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
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
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct wiphy {
    u8[6] perm_addr;
    u8[6] addr_mask;
    struct mac_address * addresses;
    const struct ieee80211_txrx_stypes * mgmt_stypes;
    const struct ieee80211_iface_combination * iface_combinations;
    int n_iface_combinations;
    u16 software_iftypes;
    u16 n_addresses;
    u16 interface_modes;
    u16 max_acl_mac_addrs;
    u32 flags;
    u32 regulatory_flags;
    u32 features;
    u8[5] ext_features;
    u32 ap_sme_capa;
    enum cfg80211_signal_type signal_type;
    int bss_priv_size;
    u8 max_scan_ssids;
    u8 max_sched_scan_reqs;
    u8 max_sched_scan_ssids;
    u8 max_match_sets;
    u16 max_scan_ie_len;
    u16 max_sched_scan_ie_len;
    u32 max_sched_scan_plans;
    u32 max_sched_scan_plan_interval;
    u32 max_sched_scan_plan_iterations;
    int n_cipher_suites;
    const u32 * cipher_suites;
    int n_akm_suites;
    const u32 * akm_suites;
    u8 retry_short;
    u8 retry_long;
    u32 frag_threshold;
    u32 rts_threshold;
    u8 coverage_class;
    char[32] fw_version;
    u32 hw_version;
    const struct wiphy_wowlan_support * wowlan;
    struct cfg80211_wowlan * wowlan_config;
    u16 max_remain_on_channel_duration;
    u8 max_num_pmkids;
    u32 available_antennas_tx;
    u32 available_antennas_rx;
    u32 probe_resp_offload;
    const u8 * extended_capabilities;
    const u8 * extended_capabilities_mask;
    u8 extended_capabilities_len;
    const struct wiphy_iftype_ext_capab * iftype_ext_capab;
    unsigned int num_iftype_ext_capab;
    const void * privid;
    struct ieee80211_supported_band *[4] bands;
    void (*)(struct wiphy *, struct regulatory_request *) reg_notifier;
    const struct ieee80211_regdomain * regd;
    struct device dev;
    bool registered;
    struct dentry * debugfsdir;
    const struct ieee80211_ht_cap * ht_capa_mod_mask;
    const struct ieee80211_vht_cap * vht_capa_mod_mask;
    struct list_head wdev_list;
    possible_net_t _net;
    const struct iw_handler_def * wext;
    const struct wiphy_coalesce_support * coalesce;
    const struct wiphy_vendor_command * vendor_commands;
    const struct nl80211_vendor_cmd_info * vendor_events;
    int n_vendor_commands;
    int n_vendor_events;
    u16 max_ap_assoc_sta;
    u8 max_num_csa_counters;
    u8 max_adj_channel_rssi_comp;
    u32 bss_select_support;
    u8 nan_supported_bands;
    u32 txq_limit;
    u32 txq_memory_limit;
    u32 txq_quantum;
    u8 support_mbssid;
    u8 support_only_he_mbssid;
    const struct cfg80211_pmsr_capabilities * pmsr_capa;
    char[0] priv;
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
<code>const struct wiphy_iftype_ext_capab * iftype_ext_capab</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_iftype_ext_capab</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head wdev_list</code>
</li>
<li>
<b>Field added. </b>
<code>u32 bss_select_support</code>
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
<code>u64 cookie_counter</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[1] ext_features</code> ➡️ <code>u8[2] ext_features</code>
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
<code>u8 max_sched_scan_reqs</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nan_supported_bands</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[2] ext_features</code> ➡️ <code>u8[3] ext_features</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 txq_limit</code>
</li>
<li>
<b>Field added. </b>
<code>u32 txq_memory_limit</code>
</li>
<li>
<b>Field added. </b>
<code>u32 txq_quantum</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[3] ext_features</code> ➡️ <code>u8[4] ext_features</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct cfg80211_pmsr_capabilities * pmsr_capa</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cookie_counter</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[4] ext_features</code> ➡️ <code>u8[5] ext_features</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int n_akm_suites</code>
</li>
<li>
<b>Field added. </b>
<code>const u32 * akm_suites</code>
</li>
<li>
<b>Field added. </b>
<code>u8 support_mbssid</code>
</li>
<li>
<b>Field added. </b>
<code>u8 support_only_he_mbssid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct ieee80211_supported_band *[3] bands</code> ➡️ <code>struct ieee80211_supported_band *[4] bands</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct wiphy_iftype_akm_suites * iftype_akm_suites</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_iftype_akm_suites</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tx_queue_len</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) tid_config_support</code>
</li>
<li>
<b>Field added. </b>
<code>u8 max_data_retry_count</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 max_adj_channel_rssi_comp</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[5] ext_features</code> ➡️ <code>u8[7] ext_features</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct cfg80211_sar_capa * sar_capa</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ieee80211_supported_band *[4] bands</code> ➡️ <code>struct ieee80211_supported_band *[5] bands</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex mtx</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[7] ext_features</code> ➡️ <code>u8[8] ext_features</code>
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
<code>struct rfkill * rfkill</code>
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
<code>u8 mbssid_max_interfaces</code>
</li>
<li>
<b>Field added. </b>
<code>u8 ema_max_profile_periodicity</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ieee80211_supported_band *[5] bands</code> ➡️ <code>struct ieee80211_supported_band *[6] bands</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 max_num_akm_suites</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 hw_timestamp_max_peers</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[8] ext_features</code> ➡️ <code>u8[9] ext_features</code>
</li>
</ul>
</details>
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
