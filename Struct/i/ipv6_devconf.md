# Struct: <code>ipv6_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    void * sysctl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __u32 ra_defrtr_metric;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __u32 ra_defrtr_metric;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    __u32 ioam6_id;
    __u32 ioam6_id_wide;
    __u8 ioam6_enabled;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __u32 ra_defrtr_metric;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    atomic_t mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    __s32 accept_untracked_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    __u32 ioam6_id;
    __u32 ioam6_id_wide;
    __u8 ioam6_enabled;
    __u8 ndisc_evict_nocarrier;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __u32 ra_defrtr_metric;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    atomic_t mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    __s32 accept_untracked_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    __u32 ioam6_id;
    __u32 ioam6_id_wide;
    __u8 ioam6_enabled;
    __u8 ndisc_evict_nocarrier;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __u32 ra_defrtr_metric;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    atomic_t mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    __s32 accept_untracked_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    __u32 ioam6_id;
    __u32 ioam6_id_wide;
    __u8 ioam6_enabled;
    __u8 ndisc_evict_nocarrier;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __u32 ra_defrtr_metric;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_min_lft;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    atomic_t mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    __s32 accept_untracked_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    __s32 rpl_seg_enabled;
    __u32 ioam6_id;
    __u32 ioam6_id_wide;
    __u8 ioam6_enabled;
    __u8 ndisc_evict_nocarrier;
    __u8 ra_honor_pio_life;
    struct ctl_table_header * sysctl_header;
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
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
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
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ipv6_devconf {
    __s32 forwarding;
    __s32 hop_limit;
    __s32 mtu6;
    __s32 accept_ra;
    __s32 accept_redirects;
    __s32 autoconf;
    __s32 dad_transmits;
    __s32 rtr_solicits;
    __s32 rtr_solicit_interval;
    __s32 rtr_solicit_max_interval;
    __s32 rtr_solicit_delay;
    __s32 force_mld_version;
    __s32 mldv1_unsolicited_report_interval;
    __s32 mldv2_unsolicited_report_interval;
    __s32 use_tempaddr;
    __s32 temp_valid_lft;
    __s32 temp_prefered_lft;
    __s32 regen_max_retry;
    __s32 max_desync_factor;
    __s32 max_addresses;
    __s32 accept_ra_defrtr;
    __s32 accept_ra_min_hop_limit;
    __s32 accept_ra_pinfo;
    __s32 ignore_routes_with_linkdown;
    __s32 accept_ra_rtr_pref;
    __s32 rtr_probe_interval;
    __s32 accept_ra_rt_info_min_plen;
    __s32 accept_ra_rt_info_max_plen;
    __s32 proxy_ndp;
    __s32 accept_source_route;
    __s32 accept_ra_from_local;
    __s32 mc_forwarding;
    __s32 disable_ipv6;
    __s32 drop_unicast_in_l2_multicast;
    __s32 accept_dad;
    __s32 force_tllao;
    __s32 ndisc_notify;
    __s32 suppress_frag_ndisc;
    __s32 accept_ra_mtu;
    __s32 drop_unsolicited_na;
    struct ipv6_stable_secret stable_secret;
    __s32 use_oif_addrs_only;
    __s32 keep_addr_on_down;
    __s32 seg6_enabled;
    __s32 seg6_require_hmac;
    __u32 enhanced_dad;
    __u32 addr_gen_mode;
    __s32 disable_policy;
    __s32 ndisc_tclass;
    struct ctl_table_header * sysctl_header;
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
<code>__s32 drop_unicast_in_l2_multicast</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 drop_unsolicited_na</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 keep_addr_on_down</code>
</li>
<li>
<b>Field added. </b>
<code>struct ctl_table_header * sysctl_header</code>
</li>
<li>
<b>Field removed. </b>
<code>void * sysctl</code>
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
<code>__s32 rtr_solicit_max_interval</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 seg6_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 seg6_require_hmac</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 enhanced_dad</code>
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
<code>__s32 accept_ra_rt_info_min_plen</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 addr_gen_mode</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 disable_policy</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__s32 ndisc_tclass</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__s32 rpl_seg_enabled</code>
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
<code>__u32 ra_defrtr_metric</code>
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
<code>__u32 ioam6_id</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 ioam6_id_wide</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 ioam6_enabled</code>
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
<code>__s32 accept_untracked_na</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 ndisc_evict_nocarrier</code>
</li>
<li>
<b>Field type changed. </b>
<code>__s32 mc_forwarding</code> ➡️ <code>atomic_t mc_forwarding</code>
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
<code>__s32 accept_ra_min_lft</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 ra_honor_pio_life</code>
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
