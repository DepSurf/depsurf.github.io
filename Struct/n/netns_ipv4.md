# Struct: <code>netns_ipv4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    struct fib_table * fib_local;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_nonlocal_bind;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    struct mr_table * mrt;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    struct fib_table * fib_local;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    unsigned int fib_seq;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    unsigned int fib_seq;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct netns_frags frags;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_autobind_reuse;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_nexthop_compat_mode;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_no_ssthresh_metrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_autobind_reuse;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_nexthop_compat_mode;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_no_ssthresh_metrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_tcp_reflect_tos;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct inet_timewait_death_row tcp_death_row;
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    unsigned int fib_rules_require_fldissect;
    bool fib_has_custom_rules;
    bool fib_has_custom_local_routes;
    bool fib_offload_disabled;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    u8 sysctl_icmp_echo_ignore_all;
    u8 sysctl_icmp_echo_enable_probe;
    u8 sysctl_icmp_echo_ignore_broadcasts;
    u8 sysctl_icmp_ignore_bogus_error_responses;
    u8 sysctl_icmp_errors_use_inbound_ifaddr;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    struct local_ports ip_local_ports;
    u8 sysctl_tcp_ecn;
    u8 sysctl_tcp_ecn_fallback;
    u8 sysctl_ip_default_ttl;
    u8 sysctl_ip_no_pmtu_disc;
    u8 sysctl_ip_fwd_use_pmtu;
    u8 sysctl_ip_fwd_update_priority;
    u8 sysctl_ip_nonlocal_bind;
    u8 sysctl_ip_autobind_reuse;
    u8 sysctl_ip_dynaddr;
    u8 sysctl_ip_early_demux;
    u8 sysctl_raw_l3mdev_accept;
    u8 sysctl_tcp_early_demux;
    u8 sysctl_udp_early_demux;
    u8 sysctl_nexthop_compat_mode;
    u8 sysctl_fwmark_reflect;
    u8 sysctl_tcp_fwmark_accept;
    u8 sysctl_tcp_l3mdev_accept;
    u8 sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_intvl;
    u8 sysctl_tcp_keepalive_probes;
    u8 sysctl_tcp_syn_retries;
    u8 sysctl_tcp_synack_retries;
    u8 sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    u8 sysctl_tcp_retries1;
    u8 sysctl_tcp_retries2;
    u8 sysctl_tcp_orphan_retries;
    u8 sysctl_tcp_tw_reuse;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    u8 sysctl_tcp_sack;
    u8 sysctl_tcp_window_scaling;
    u8 sysctl_tcp_timestamps;
    u8 sysctl_tcp_early_retrans;
    u8 sysctl_tcp_recovery;
    u8 sysctl_tcp_thin_linear_timeouts;
    u8 sysctl_tcp_slow_start_after_idle;
    u8 sysctl_tcp_retrans_collapse;
    u8 sysctl_tcp_stdurg;
    u8 sysctl_tcp_rfc1337;
    u8 sysctl_tcp_abort_on_overflow;
    u8 sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_adv_win_scale;
    u8 sysctl_tcp_dsack;
    u8 sysctl_tcp_app_win;
    u8 sysctl_tcp_frto;
    u8 sysctl_tcp_nometrics_save;
    u8 sysctl_tcp_no_ssthresh_metrics_save;
    u8 sysctl_tcp_moderate_rcvbuf;
    u8 sysctl_tcp_tso_win_divisor;
    u8 sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_rtt_wlen;
    u8 sysctl_tcp_min_tso_segs;
    u8 sysctl_tcp_autocorking;
    u8 sysctl_tcp_reflect_tos;
    u8 sysctl_tcp_comp_sack_nr;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    u8 sysctl_fib_notify_on_flag_change;
    u8 sysctl_udp_l3mdev_accept;
    u8 sysctl_igmp_llm_reports;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    u8 sysctl_fib_multipath_use_neigh;
    u8 sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct inet_timewait_death_row tcp_death_row;
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    unsigned int fib_rules_require_fldissect;
    bool fib_has_custom_rules;
    bool fib_has_custom_local_routes;
    bool fib_offload_disabled;
    atomic_t fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    u8 sysctl_icmp_echo_ignore_all;
    u8 sysctl_icmp_echo_enable_probe;
    u8 sysctl_icmp_echo_ignore_broadcasts;
    u8 sysctl_icmp_ignore_bogus_error_responses;
    u8 sysctl_icmp_errors_use_inbound_ifaddr;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    struct local_ports ip_local_ports;
    u8 sysctl_tcp_ecn;
    u8 sysctl_tcp_ecn_fallback;
    u8 sysctl_ip_default_ttl;
    u8 sysctl_ip_no_pmtu_disc;
    u8 sysctl_ip_fwd_use_pmtu;
    u8 sysctl_ip_fwd_update_priority;
    u8 sysctl_ip_nonlocal_bind;
    u8 sysctl_ip_autobind_reuse;
    u8 sysctl_ip_dynaddr;
    u8 sysctl_ip_early_demux;
    u8 sysctl_raw_l3mdev_accept;
    u8 sysctl_tcp_early_demux;
    u8 sysctl_udp_early_demux;
    u8 sysctl_nexthop_compat_mode;
    u8 sysctl_fwmark_reflect;
    u8 sysctl_tcp_fwmark_accept;
    u8 sysctl_tcp_l3mdev_accept;
    u8 sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_intvl;
    u8 sysctl_tcp_keepalive_probes;
    u8 sysctl_tcp_syn_retries;
    u8 sysctl_tcp_synack_retries;
    u8 sysctl_tcp_syncookies;
    u8 sysctl_tcp_migrate_req;
    int sysctl_tcp_reordering;
    u8 sysctl_tcp_retries1;
    u8 sysctl_tcp_retries2;
    u8 sysctl_tcp_orphan_retries;
    u8 sysctl_tcp_tw_reuse;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    u8 sysctl_tcp_sack;
    u8 sysctl_tcp_window_scaling;
    u8 sysctl_tcp_timestamps;
    u8 sysctl_tcp_early_retrans;
    u8 sysctl_tcp_recovery;
    u8 sysctl_tcp_thin_linear_timeouts;
    u8 sysctl_tcp_slow_start_after_idle;
    u8 sysctl_tcp_retrans_collapse;
    u8 sysctl_tcp_stdurg;
    u8 sysctl_tcp_rfc1337;
    u8 sysctl_tcp_abort_on_overflow;
    u8 sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_adv_win_scale;
    u8 sysctl_tcp_dsack;
    u8 sysctl_tcp_app_win;
    u8 sysctl_tcp_frto;
    u8 sysctl_tcp_nometrics_save;
    u8 sysctl_tcp_no_ssthresh_metrics_save;
    u8 sysctl_tcp_moderate_rcvbuf;
    u8 sysctl_tcp_tso_win_divisor;
    u8 sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_rtt_wlen;
    u8 sysctl_tcp_min_tso_segs;
    u8 sysctl_tcp_autocorking;
    u8 sysctl_tcp_reflect_tos;
    u8 sysctl_tcp_comp_sack_nr;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    u8 sysctl_fib_notify_on_flag_change;
    u8 sysctl_udp_l3mdev_accept;
    u8 sysctl_igmp_llm_reports;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    u32 sysctl_fib_multipath_hash_fields;
    u8 sysctl_fib_multipath_use_neigh;
    u8 sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct inet_timewait_death_row * tcp_death_row;
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    unsigned int fib_rules_require_fldissect;
    bool fib_has_custom_rules;
    bool fib_has_custom_local_routes;
    bool fib_offload_disabled;
    atomic_t fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    struct sock * fibnl;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    u8 sysctl_icmp_echo_ignore_all;
    u8 sysctl_icmp_echo_enable_probe;
    u8 sysctl_icmp_echo_ignore_broadcasts;
    u8 sysctl_icmp_ignore_bogus_error_responses;
    u8 sysctl_icmp_errors_use_inbound_ifaddr;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    u32 ip_rt_min_pmtu;
    int ip_rt_mtu_expires;
    int ip_rt_min_advmss;
    struct local_ports ip_local_ports;
    u8 sysctl_tcp_ecn;
    u8 sysctl_tcp_ecn_fallback;
    u8 sysctl_ip_default_ttl;
    u8 sysctl_ip_no_pmtu_disc;
    u8 sysctl_ip_fwd_use_pmtu;
    u8 sysctl_ip_fwd_update_priority;
    u8 sysctl_ip_nonlocal_bind;
    u8 sysctl_ip_autobind_reuse;
    u8 sysctl_ip_dynaddr;
    u8 sysctl_ip_early_demux;
    u8 sysctl_raw_l3mdev_accept;
    u8 sysctl_tcp_early_demux;
    u8 sysctl_udp_early_demux;
    u8 sysctl_nexthop_compat_mode;
    u8 sysctl_fwmark_reflect;
    u8 sysctl_tcp_fwmark_accept;
    u8 sysctl_tcp_l3mdev_accept;
    u8 sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_intvl;
    u8 sysctl_tcp_keepalive_probes;
    u8 sysctl_tcp_syn_retries;
    u8 sysctl_tcp_synack_retries;
    u8 sysctl_tcp_syncookies;
    u8 sysctl_tcp_migrate_req;
    u8 sysctl_tcp_comp_sack_nr;
    int sysctl_tcp_reordering;
    u8 sysctl_tcp_retries1;
    u8 sysctl_tcp_retries2;
    u8 sysctl_tcp_orphan_retries;
    u8 sysctl_tcp_tw_reuse;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    u8 sysctl_tcp_sack;
    u8 sysctl_tcp_window_scaling;
    u8 sysctl_tcp_timestamps;
    u8 sysctl_tcp_early_retrans;
    u8 sysctl_tcp_recovery;
    u8 sysctl_tcp_thin_linear_timeouts;
    u8 sysctl_tcp_slow_start_after_idle;
    u8 sysctl_tcp_retrans_collapse;
    u8 sysctl_tcp_stdurg;
    u8 sysctl_tcp_rfc1337;
    u8 sysctl_tcp_abort_on_overflow;
    u8 sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_adv_win_scale;
    u8 sysctl_tcp_dsack;
    u8 sysctl_tcp_app_win;
    u8 sysctl_tcp_frto;
    u8 sysctl_tcp_nometrics_save;
    u8 sysctl_tcp_no_ssthresh_metrics_save;
    u8 sysctl_tcp_moderate_rcvbuf;
    u8 sysctl_tcp_tso_win_divisor;
    u8 sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_rtt_wlen;
    u8 sysctl_tcp_min_tso_segs;
    u8 sysctl_tcp_tso_rtt_log;
    u8 sysctl_tcp_autocorking;
    u8 sysctl_tcp_reflect_tos;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    u8 sysctl_fib_notify_on_flag_change;
    u8 sysctl_udp_l3mdev_accept;
    u8 sysctl_igmp_llm_reports;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    u32 sysctl_fib_multipath_hash_fields;
    u8 sysctl_fib_multipath_use_neigh;
    u8 sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct inet_timewait_death_row tcp_death_row;
    struct udp_table * udp_table;
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    unsigned int fib_rules_require_fldissect;
    bool fib_has_custom_rules;
    bool fib_has_custom_local_routes;
    bool fib_offload_disabled;
    atomic_t fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    struct sock * fibnl;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    u8 sysctl_icmp_echo_ignore_all;
    u8 sysctl_icmp_echo_enable_probe;
    u8 sysctl_icmp_echo_ignore_broadcasts;
    u8 sysctl_icmp_ignore_bogus_error_responses;
    u8 sysctl_icmp_errors_use_inbound_ifaddr;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    u32 ip_rt_min_pmtu;
    int ip_rt_mtu_expires;
    int ip_rt_min_advmss;
    struct local_ports ip_local_ports;
    u8 sysctl_tcp_ecn;
    u8 sysctl_tcp_ecn_fallback;
    u8 sysctl_ip_default_ttl;
    u8 sysctl_ip_no_pmtu_disc;
    u8 sysctl_ip_fwd_use_pmtu;
    u8 sysctl_ip_fwd_update_priority;
    u8 sysctl_ip_nonlocal_bind;
    u8 sysctl_ip_autobind_reuse;
    u8 sysctl_ip_dynaddr;
    u8 sysctl_ip_early_demux;
    u8 sysctl_raw_l3mdev_accept;
    u8 sysctl_tcp_early_demux;
    u8 sysctl_udp_early_demux;
    u8 sysctl_nexthop_compat_mode;
    u8 sysctl_fwmark_reflect;
    u8 sysctl_tcp_fwmark_accept;
    u8 sysctl_tcp_l3mdev_accept;
    u8 sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_intvl;
    u8 sysctl_tcp_keepalive_probes;
    u8 sysctl_tcp_syn_retries;
    u8 sysctl_tcp_synack_retries;
    u8 sysctl_tcp_syncookies;
    u8 sysctl_tcp_migrate_req;
    u8 sysctl_tcp_comp_sack_nr;
    int sysctl_tcp_reordering;
    u8 sysctl_tcp_retries1;
    u8 sysctl_tcp_retries2;
    u8 sysctl_tcp_orphan_retries;
    u8 sysctl_tcp_tw_reuse;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    u8 sysctl_tcp_sack;
    u8 sysctl_tcp_window_scaling;
    u8 sysctl_tcp_timestamps;
    u8 sysctl_tcp_early_retrans;
    u8 sysctl_tcp_recovery;
    u8 sysctl_tcp_thin_linear_timeouts;
    u8 sysctl_tcp_slow_start_after_idle;
    u8 sysctl_tcp_retrans_collapse;
    u8 sysctl_tcp_stdurg;
    u8 sysctl_tcp_rfc1337;
    u8 sysctl_tcp_abort_on_overflow;
    u8 sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_adv_win_scale;
    u8 sysctl_tcp_dsack;
    u8 sysctl_tcp_app_win;
    u8 sysctl_tcp_frto;
    u8 sysctl_tcp_nometrics_save;
    u8 sysctl_tcp_no_ssthresh_metrics_save;
    u8 sysctl_tcp_moderate_rcvbuf;
    u8 sysctl_tcp_tso_win_divisor;
    u8 sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_rtt_wlen;
    u8 sysctl_tcp_min_tso_segs;
    u8 sysctl_tcp_tso_rtt_log;
    u8 sysctl_tcp_autocorking;
    u8 sysctl_tcp_reflect_tos;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    unsigned int sysctl_tcp_child_ehash_entries;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    u32 tcp_challenge_timestamp;
    u32 tcp_challenge_count;
    u8 sysctl_tcp_plb_enabled;
    u8 sysctl_tcp_plb_idle_rehash_rounds;
    u8 sysctl_tcp_plb_rehash_rounds;
    u8 sysctl_tcp_plb_suspend_rto_sec;
    int sysctl_tcp_plb_cong_thresh;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    u8 sysctl_fib_notify_on_flag_change;
    u8 sysctl_udp_l3mdev_accept;
    u8 sysctl_igmp_llm_reports;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    unsigned int sysctl_udp_child_hash_entries;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    u32 sysctl_fib_multipath_hash_fields;
    u8 sysctl_fib_multipath_use_neigh;
    u8 sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct inet_timewait_death_row tcp_death_row;
    struct udp_table * udp_table;
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    unsigned int fib_rules_require_fldissect;
    bool fib_has_custom_rules;
    bool fib_has_custom_local_routes;
    bool fib_offload_disabled;
    u8 sysctl_tcp_shrink_window;
    atomic_t fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    struct sock * fibnl;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    u8 sysctl_icmp_echo_ignore_all;
    u8 sysctl_icmp_echo_enable_probe;
    u8 sysctl_icmp_echo_ignore_broadcasts;
    u8 sysctl_icmp_ignore_bogus_error_responses;
    u8 sysctl_icmp_errors_use_inbound_ifaddr;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    u32 ip_rt_min_pmtu;
    int ip_rt_mtu_expires;
    int ip_rt_min_advmss;
    struct local_ports ip_local_ports;
    u8 sysctl_tcp_ecn;
    u8 sysctl_tcp_ecn_fallback;
    u8 sysctl_ip_default_ttl;
    u8 sysctl_ip_no_pmtu_disc;
    u8 sysctl_ip_fwd_use_pmtu;
    u8 sysctl_ip_fwd_update_priority;
    u8 sysctl_ip_nonlocal_bind;
    u8 sysctl_ip_autobind_reuse;
    u8 sysctl_ip_dynaddr;
    u8 sysctl_ip_early_demux;
    u8 sysctl_raw_l3mdev_accept;
    u8 sysctl_tcp_early_demux;
    u8 sysctl_udp_early_demux;
    u8 sysctl_nexthop_compat_mode;
    u8 sysctl_fwmark_reflect;
    u8 sysctl_tcp_fwmark_accept;
    u8 sysctl_tcp_l3mdev_accept;
    u8 sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_intvl;
    u8 sysctl_tcp_keepalive_probes;
    u8 sysctl_tcp_syn_retries;
    u8 sysctl_tcp_synack_retries;
    u8 sysctl_tcp_syncookies;
    u8 sysctl_tcp_migrate_req;
    u8 sysctl_tcp_comp_sack_nr;
    int sysctl_tcp_reordering;
    u8 sysctl_tcp_retries1;
    u8 sysctl_tcp_retries2;
    u8 sysctl_tcp_orphan_retries;
    u8 sysctl_tcp_tw_reuse;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    u8 sysctl_tcp_sack;
    u8 sysctl_tcp_window_scaling;
    u8 sysctl_tcp_timestamps;
    u8 sysctl_tcp_early_retrans;
    u8 sysctl_tcp_recovery;
    u8 sysctl_tcp_thin_linear_timeouts;
    u8 sysctl_tcp_slow_start_after_idle;
    u8 sysctl_tcp_retrans_collapse;
    u8 sysctl_tcp_stdurg;
    u8 sysctl_tcp_rfc1337;
    u8 sysctl_tcp_abort_on_overflow;
    u8 sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_adv_win_scale;
    u8 sysctl_tcp_dsack;
    u8 sysctl_tcp_app_win;
    u8 sysctl_tcp_frto;
    u8 sysctl_tcp_nometrics_save;
    u8 sysctl_tcp_no_ssthresh_metrics_save;
    u8 sysctl_tcp_moderate_rcvbuf;
    u8 sysctl_tcp_tso_win_divisor;
    u8 sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_rtt_wlen;
    u8 sysctl_tcp_min_tso_segs;
    u8 sysctl_tcp_tso_rtt_log;
    u8 sysctl_tcp_autocorking;
    u8 sysctl_tcp_reflect_tos;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    unsigned int sysctl_tcp_child_ehash_entries;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    u32 tcp_challenge_timestamp;
    u32 tcp_challenge_count;
    u8 sysctl_tcp_plb_enabled;
    u8 sysctl_tcp_plb_idle_rehash_rounds;
    u8 sysctl_tcp_plb_rehash_rounds;
    u8 sysctl_tcp_plb_suspend_rto_sec;
    int sysctl_tcp_plb_cong_thresh;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    u8 sysctl_fib_notify_on_flag_change;
    u8 sysctl_tcp_syn_linear_timeouts;
    u8 sysctl_udp_l3mdev_accept;
    u8 sysctl_igmp_llm_reports;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    unsigned int sysctl_udp_child_hash_entries;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    u32 sysctl_fib_multipath_hash_fields;
    u8 sysctl_fib_multipath_use_neigh;
    u8 sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    __u8[0] __cacheline_group_begin__netns_ipv4_read_tx;
    u8 sysctl_tcp_early_retrans;
    u8 sysctl_tcp_tso_win_divisor;
    u8 sysctl_tcp_tso_rtt_log;
    u8 sysctl_tcp_autocorking;
    int sysctl_tcp_min_snd_mss;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_min_rtt_wlen;
    int[3] sysctl_tcp_wmem;
    u8 sysctl_ip_fwd_use_pmtu;
    __u8[0] __cacheline_group_end__netns_ipv4_read_tx;
    __u8[0] __cacheline_group_begin__netns_ipv4_read_txrx;
    u8 sysctl_tcp_moderate_rcvbuf;
    __u8[0] __cacheline_group_end__netns_ipv4_read_txrx;
    __u8[0] __cacheline_group_begin__netns_ipv4_read_rx;
    u8 sysctl_ip_early_demux;
    u8 sysctl_tcp_early_demux;
    int sysctl_tcp_reordering;
    int[3] sysctl_tcp_rmem;
    __u8[0] __cacheline_group_end__netns_ipv4_read_rx;
    struct inet_timewait_death_row tcp_death_row;
    struct udp_table * udp_table;
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    unsigned int fib_rules_require_fldissect;
    bool fib_has_custom_rules;
    bool fib_has_custom_local_routes;
    bool fib_offload_disabled;
    u8 sysctl_tcp_shrink_window;
    atomic_t fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    struct sock * fibnl;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    u8 sysctl_icmp_echo_ignore_all;
    u8 sysctl_icmp_echo_enable_probe;
    u8 sysctl_icmp_echo_ignore_broadcasts;
    u8 sysctl_icmp_ignore_bogus_error_responses;
    u8 sysctl_icmp_errors_use_inbound_ifaddr;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    u32 ip_rt_min_pmtu;
    int ip_rt_mtu_expires;
    int ip_rt_min_advmss;
    struct local_ports ip_local_ports;
    u8 sysctl_tcp_ecn;
    u8 sysctl_tcp_ecn_fallback;
    u8 sysctl_ip_default_ttl;
    u8 sysctl_ip_no_pmtu_disc;
    u8 sysctl_ip_fwd_update_priority;
    u8 sysctl_ip_nonlocal_bind;
    u8 sysctl_ip_autobind_reuse;
    u8 sysctl_ip_dynaddr;
    u8 sysctl_raw_l3mdev_accept;
    u8 sysctl_udp_early_demux;
    u8 sysctl_nexthop_compat_mode;
    u8 sysctl_fwmark_reflect;
    u8 sysctl_tcp_fwmark_accept;
    u8 sysctl_tcp_l3mdev_accept;
    u8 sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_intvl;
    u8 sysctl_tcp_keepalive_probes;
    u8 sysctl_tcp_syn_retries;
    u8 sysctl_tcp_synack_retries;
    u8 sysctl_tcp_syncookies;
    u8 sysctl_tcp_migrate_req;
    u8 sysctl_tcp_comp_sack_nr;
    u8 sysctl_tcp_backlog_ack_defer;
    u8 sysctl_tcp_pingpong_thresh;
    u8 sysctl_tcp_retries1;
    u8 sysctl_tcp_retries2;
    u8 sysctl_tcp_orphan_retries;
    u8 sysctl_tcp_tw_reuse;
    int sysctl_tcp_fin_timeout;
    u8 sysctl_tcp_sack;
    u8 sysctl_tcp_window_scaling;
    u8 sysctl_tcp_timestamps;
    u8 sysctl_tcp_recovery;
    u8 sysctl_tcp_thin_linear_timeouts;
    u8 sysctl_tcp_slow_start_after_idle;
    u8 sysctl_tcp_retrans_collapse;
    u8 sysctl_tcp_stdurg;
    u8 sysctl_tcp_rfc1337;
    u8 sysctl_tcp_abort_on_overflow;
    u8 sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_adv_win_scale;
    u8 sysctl_tcp_dsack;
    u8 sysctl_tcp_app_win;
    u8 sysctl_tcp_frto;
    u8 sysctl_tcp_nometrics_save;
    u8 sysctl_tcp_no_ssthresh_metrics_save;
    u8 sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_challenge_ack_limit;
    u8 sysctl_tcp_min_tso_segs;
    u8 sysctl_tcp_reflect_tos;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    unsigned int sysctl_tcp_child_ehash_entries;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    long unsigned int sysctl_tcp_comp_sack_slack_ns;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    u32 tcp_challenge_timestamp;
    u32 tcp_challenge_count;
    u8 sysctl_tcp_plb_enabled;
    u8 sysctl_tcp_plb_idle_rehash_rounds;
    u8 sysctl_tcp_plb_rehash_rounds;
    u8 sysctl_tcp_plb_suspend_rto_sec;
    int sysctl_tcp_plb_cong_thresh;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    u8 sysctl_fib_notify_on_flag_change;
    u8 sysctl_tcp_syn_linear_timeouts;
    u8 sysctl_udp_l3mdev_accept;
    u8 sysctl_igmp_llm_reports;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    unsigned int sysctl_udp_child_hash_entries;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    u32 sysctl_fib_multipath_hash_fields;
    u8 sysctl_fib_multipath_use_neigh;
    u8 sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
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
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
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
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct mr_table * mrt;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netns_ipv4 {
    struct ctl_table_header * forw_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * ipv4_hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * xfrm4_hdr;
    struct ipv4_devconf * devconf_all;
    struct ipv4_devconf * devconf_dflt;
    struct ip_ra_chain * ra_chain;
    struct mutex ra_mutex;
    struct fib_rules_ops * rules_ops;
    bool fib_has_custom_rules;
    unsigned int fib_rules_require_fldissect;
    struct fib_table * fib_main;
    struct fib_table * fib_default;
    bool fib_has_custom_local_routes;
    int fib_num_tclassid_users;
    struct hlist_head * fib_table_hash;
    bool fib_offload_disabled;
    struct sock * fibnl;
    struct sock * * icmp_sk;
    struct sock * mc_autojoin_sk;
    struct inet_peer_base * peers;
    struct sock * * tcp_sk;
    struct fqdir * fqdir;
    struct xt_table * iptable_filter;
    struct xt_table * iptable_mangle;
    struct xt_table * iptable_raw;
    struct xt_table * arptable_filter;
    struct xt_table * iptable_security;
    struct xt_table * nat_table;
    int sysctl_icmp_echo_ignore_all;
    int sysctl_icmp_echo_ignore_broadcasts;
    int sysctl_icmp_ignore_bogus_error_responses;
    int sysctl_icmp_ratelimit;
    int sysctl_icmp_ratemask;
    int sysctl_icmp_errors_use_inbound_ifaddr;
    struct local_ports ip_local_ports;
    int sysctl_tcp_ecn;
    int sysctl_tcp_ecn_fallback;
    int sysctl_ip_default_ttl;
    int sysctl_ip_no_pmtu_disc;
    int sysctl_ip_fwd_use_pmtu;
    int sysctl_ip_fwd_update_priority;
    int sysctl_ip_nonlocal_bind;
    int sysctl_ip_dynaddr;
    int sysctl_ip_early_demux;
    int sysctl_raw_l3mdev_accept;
    int sysctl_tcp_early_demux;
    int sysctl_udp_early_demux;
    int sysctl_fwmark_reflect;
    int sysctl_tcp_fwmark_accept;
    int sysctl_tcp_l3mdev_accept;
    int sysctl_tcp_mtu_probing;
    int sysctl_tcp_mtu_probe_floor;
    int sysctl_tcp_base_mss;
    int sysctl_tcp_min_snd_mss;
    int sysctl_tcp_probe_threshold;
    u32 sysctl_tcp_probe_interval;
    int sysctl_tcp_keepalive_time;
    int sysctl_tcp_keepalive_probes;
    int sysctl_tcp_keepalive_intvl;
    int sysctl_tcp_syn_retries;
    int sysctl_tcp_synack_retries;
    int sysctl_tcp_syncookies;
    int sysctl_tcp_reordering;
    int sysctl_tcp_retries1;
    int sysctl_tcp_retries2;
    int sysctl_tcp_orphan_retries;
    int sysctl_tcp_fin_timeout;
    unsigned int sysctl_tcp_notsent_lowat;
    int sysctl_tcp_tw_reuse;
    int sysctl_tcp_sack;
    int sysctl_tcp_window_scaling;
    int sysctl_tcp_timestamps;
    int sysctl_tcp_early_retrans;
    int sysctl_tcp_recovery;
    int sysctl_tcp_thin_linear_timeouts;
    int sysctl_tcp_slow_start_after_idle;
    int sysctl_tcp_retrans_collapse;
    int sysctl_tcp_stdurg;
    int sysctl_tcp_rfc1337;
    int sysctl_tcp_abort_on_overflow;
    int sysctl_tcp_fack;
    int sysctl_tcp_max_reordering;
    int sysctl_tcp_dsack;
    int sysctl_tcp_app_win;
    int sysctl_tcp_adv_win_scale;
    int sysctl_tcp_frto;
    int sysctl_tcp_nometrics_save;
    int sysctl_tcp_moderate_rcvbuf;
    int sysctl_tcp_tso_win_divisor;
    int sysctl_tcp_workaround_signed_windows;
    int sysctl_tcp_limit_output_bytes;
    int sysctl_tcp_challenge_ack_limit;
    int sysctl_tcp_min_tso_segs;
    int sysctl_tcp_min_rtt_wlen;
    int sysctl_tcp_autocorking;
    int sysctl_tcp_invalid_ratelimit;
    int sysctl_tcp_pacing_ss_ratio;
    int sysctl_tcp_pacing_ca_ratio;
    int[3] sysctl_tcp_wmem;
    int[3] sysctl_tcp_rmem;
    int sysctl_tcp_comp_sack_nr;
    long unsigned int sysctl_tcp_comp_sack_delay_ns;
    struct inet_timewait_death_row tcp_death_row;
    int sysctl_max_syn_backlog;
    int sysctl_tcp_fastopen;
    const struct tcp_congestion_ops * tcp_congestion_control;
    struct tcp_fastopen_context * tcp_fastopen_ctx;
    spinlock_t tcp_fastopen_ctx_lock;
    unsigned int sysctl_tcp_fastopen_blackhole_timeout;
    atomic_t tfo_active_disable_times;
    long unsigned int tfo_active_disable_stamp;
    int sysctl_udp_wmem_min;
    int sysctl_udp_rmem_min;
    int sysctl_udp_l3mdev_accept;
    int sysctl_igmp_max_memberships;
    int sysctl_igmp_max_msf;
    int sysctl_igmp_llm_reports;
    int sysctl_igmp_qrv;
    struct ping_group_range ping_group_range;
    atomic_t dev_addr_genid;
    long unsigned int * sysctl_local_reserved_ports;
    int sysctl_ip_prot_sock;
    struct list_head mr_tables;
    struct fib_rules_ops * mr_rules_ops;
    int sysctl_fib_multipath_use_neigh;
    int sysctl_fib_multipath_hash_policy;
    struct fib_notifier_ops * notifier_ops;
    unsigned int fib_seq;
    struct fib_notifier_ops * ipmr_notifier_ops;
    unsigned int ipmr_seq;
    atomic_t rt_genid;
    siphash_key_t ip_id_key;
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
<code>int sysctl_ip_default_ttl</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_ip_dynaddr</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_ip_early_demux</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_l3mdev_accept</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_keepalive_time</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_keepalive_probes</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_keepalive_intvl</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_syn_retries</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_synack_retries</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_syncookies</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_reordering</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_retries1</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_retries2</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_orphan_retries</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_fin_timeout</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sysctl_tcp_notsent_lowat</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_igmp_max_memberships</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_igmp_max_msf</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_igmp_llm_reports</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_igmp_qrv</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_fib_multipath_use_neigh</code>
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
<code>int sysctl_tcp_tw_reuse</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int fib_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fib_table * fib_local</code>
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
<code>int sysctl_tcp_early_demux</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_udp_early_demux</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_sack</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_window_scaling</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_timestamps</code>
</li>
<li>
<b>Field added. </b>
<code>struct inet_timewait_death_row tcp_death_row</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_max_syn_backlog</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_udp_l3mdev_accept</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_ip_prot_sock</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_fib_multipath_hash_policy</code>
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
<code>bool fib_has_custom_local_routes</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_early_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_recovery</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_thin_linear_timeouts</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_slow_start_after_idle</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_retrans_collapse</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_stdurg</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_rfc1337</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_abort_on_overflow</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_fack</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_max_reordering</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_dsack</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_app_win</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_adv_win_scale</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_frto</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_nometrics_save</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_moderate_rcvbuf</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_tso_win_divisor</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_workaround_signed_windows</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_limit_output_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_challenge_ack_limit</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_min_tso_segs</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_min_rtt_wlen</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_autocorking</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_invalid_ratelimit</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_pacing_ss_ratio</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_pacing_ca_ratio</code>
</li>
<li>
<b>Field added. </b>
<code>int[3] sysctl_tcp_wmem</code>
</li>
<li>
<b>Field added. </b>
<code>int[3] sysctl_tcp_rmem</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_fastopen</code>
</li>
<li>
<b>Field added. </b>
<code>const struct tcp_congestion_ops * tcp_congestion_control</code>
</li>
<li>
<b>Field added. </b>
<code>struct tcp_fastopen_context * tcp_fastopen_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t tcp_fastopen_ctx_lock</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sysctl_tcp_fastopen_blackhole_timeout</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t tfo_active_disable_times</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tfo_active_disable_stamp</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_notifier_ops * notifier_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_notifier_ops * ipmr_notifier_ops</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ipmr_seq</code>
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
<code>struct ip_ra_chain * ra_chain</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex ra_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int fib_rules_require_fldissect</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_comp_sack_nr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int sysctl_tcp_comp_sack_delay_ns</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_udp_wmem_min</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_udp_rmem_min</code>
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
<code>int sysctl_ip_fwd_update_priority</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_raw_l3mdev_accept</code>
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
<code>struct fqdir * fqdir</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_min_snd_mss</code>
</li>
<li>
<b>Field added. </b>
<code>siphash_key_t ip_id_key</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netns_frags frags</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * iptable_filter</code> ➡️ <code>struct xt_table * iptable_filter</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * iptable_mangle</code> ➡️ <code>struct xt_table * iptable_mangle</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * iptable_raw</code> ➡️ <code>struct xt_table * iptable_raw</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * arptable_filter</code> ➡️ <code>struct xt_table * arptable_filter</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * iptable_security</code> ➡️ <code>struct xt_table * iptable_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * nat_table</code> ➡️ <code>struct xt_table * nat_table</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_mtu_probe_floor</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mr_tables</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_rules_ops * mr_rules_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mr_table * mrt</code>
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
<code>int sysctl_ip_autobind_reuse</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_nexthop_compat_mode</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_no_ssthresh_metrics_save</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int sysctl_tcp_comp_sack_slack_ns</code>
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
<code>int sysctl_tcp_reflect_tos</code>
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
<code>u8 sysctl_icmp_echo_enable_probe</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_fib_notify_on_flag_change</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * iptable_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * iptable_mangle</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * iptable_raw</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * arptable_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * iptable_security</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * nat_table</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_icmp_echo_ignore_all</code> ➡️ <code>u8 sysctl_icmp_echo_ignore_all</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_icmp_echo_ignore_broadcasts</code> ➡️ <code>u8 sysctl_icmp_echo_ignore_broadcasts</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_icmp_ignore_bogus_error_responses</code> ➡️ <code>u8 sysctl_icmp_ignore_bogus_error_responses</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_icmp_errors_use_inbound_ifaddr</code> ➡️ <code>u8 sysctl_icmp_errors_use_inbound_ifaddr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_ecn</code> ➡️ <code>u8 sysctl_tcp_ecn</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_ecn_fallback</code> ➡️ <code>u8 sysctl_tcp_ecn_fallback</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_default_ttl</code> ➡️ <code>u8 sysctl_ip_default_ttl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_no_pmtu_disc</code> ➡️ <code>u8 sysctl_ip_no_pmtu_disc</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_fwd_use_pmtu</code> ➡️ <code>u8 sysctl_ip_fwd_use_pmtu</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_fwd_update_priority</code> ➡️ <code>u8 sysctl_ip_fwd_update_priority</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_nonlocal_bind</code> ➡️ <code>u8 sysctl_ip_nonlocal_bind</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_autobind_reuse</code> ➡️ <code>u8 sysctl_ip_autobind_reuse</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_dynaddr</code> ➡️ <code>u8 sysctl_ip_dynaddr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_ip_early_demux</code> ➡️ <code>u8 sysctl_ip_early_demux</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_raw_l3mdev_accept</code> ➡️ <code>u8 sysctl_raw_l3mdev_accept</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_early_demux</code> ➡️ <code>u8 sysctl_tcp_early_demux</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_udp_early_demux</code> ➡️ <code>u8 sysctl_udp_early_demux</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_nexthop_compat_mode</code> ➡️ <code>u8 sysctl_nexthop_compat_mode</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_fwmark_reflect</code> ➡️ <code>u8 sysctl_fwmark_reflect</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_fwmark_accept</code> ➡️ <code>u8 sysctl_tcp_fwmark_accept</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_l3mdev_accept</code> ➡️ <code>u8 sysctl_tcp_l3mdev_accept</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_mtu_probing</code> ➡️ <code>u8 sysctl_tcp_mtu_probing</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_keepalive_probes</code> ➡️ <code>u8 sysctl_tcp_keepalive_probes</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_syn_retries</code> ➡️ <code>u8 sysctl_tcp_syn_retries</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_synack_retries</code> ➡️ <code>u8 sysctl_tcp_synack_retries</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_syncookies</code> ➡️ <code>u8 sysctl_tcp_syncookies</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_retries1</code> ➡️ <code>u8 sysctl_tcp_retries1</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_retries2</code> ➡️ <code>u8 sysctl_tcp_retries2</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_orphan_retries</code> ➡️ <code>u8 sysctl_tcp_orphan_retries</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_tw_reuse</code> ➡️ <code>u8 sysctl_tcp_tw_reuse</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_sack</code> ➡️ <code>u8 sysctl_tcp_sack</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_window_scaling</code> ➡️ <code>u8 sysctl_tcp_window_scaling</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_timestamps</code> ➡️ <code>u8 sysctl_tcp_timestamps</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_early_retrans</code> ➡️ <code>u8 sysctl_tcp_early_retrans</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_recovery</code> ➡️ <code>u8 sysctl_tcp_recovery</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_thin_linear_timeouts</code> ➡️ <code>u8 sysctl_tcp_thin_linear_timeouts</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_slow_start_after_idle</code> ➡️ <code>u8 sysctl_tcp_slow_start_after_idle</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_retrans_collapse</code> ➡️ <code>u8 sysctl_tcp_retrans_collapse</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_stdurg</code> ➡️ <code>u8 sysctl_tcp_stdurg</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_rfc1337</code> ➡️ <code>u8 sysctl_tcp_rfc1337</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_abort_on_overflow</code> ➡️ <code>u8 sysctl_tcp_abort_on_overflow</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_fack</code> ➡️ <code>u8 sysctl_tcp_fack</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_dsack</code> ➡️ <code>u8 sysctl_tcp_dsack</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_app_win</code> ➡️ <code>u8 sysctl_tcp_app_win</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_frto</code> ➡️ <code>u8 sysctl_tcp_frto</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_nometrics_save</code> ➡️ <code>u8 sysctl_tcp_nometrics_save</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_no_ssthresh_metrics_save</code> ➡️ <code>u8 sysctl_tcp_no_ssthresh_metrics_save</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_moderate_rcvbuf</code> ➡️ <code>u8 sysctl_tcp_moderate_rcvbuf</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_tso_win_divisor</code> ➡️ <code>u8 sysctl_tcp_tso_win_divisor</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_workaround_signed_windows</code> ➡️ <code>u8 sysctl_tcp_workaround_signed_windows</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_min_tso_segs</code> ➡️ <code>u8 sysctl_tcp_min_tso_segs</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_autocorking</code> ➡️ <code>u8 sysctl_tcp_autocorking</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_comp_sack_nr</code> ➡️ <code>u8 sysctl_tcp_comp_sack_nr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_tcp_reflect_tos</code> ➡️ <code>u8 sysctl_tcp_reflect_tos</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_udp_l3mdev_accept</code> ➡️ <code>u8 sysctl_udp_l3mdev_accept</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_igmp_llm_reports</code> ➡️ <code>u8 sysctl_igmp_llm_reports</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_fib_multipath_use_neigh</code> ➡️ <code>u8 sysctl_fib_multipath_use_neigh</code>
</li>
<li>
<b>Field type changed. </b>
<code>int sysctl_fib_multipath_hash_policy</code> ➡️ <code>u8 sysctl_fib_multipath_hash_policy</code>
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
<code>u8 sysctl_tcp_migrate_req</code>
</li>
<li>
<b>Field added. </b>
<code>u32 sysctl_fib_multipath_hash_fields</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t tcp_fastopen_ctx_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>int fib_num_tclassid_users</code> ➡️ <code>atomic_t fib_num_tclassid_users</code>
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
<code>u32 ip_rt_min_pmtu</code>
</li>
<li>
<b>Field added. </b>
<code>int ip_rt_mtu_expires</code>
</li>
<li>
<b>Field added. </b>
<code>int ip_rt_min_advmss</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_tso_rtt_log</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * * icmp_sk</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * * tcp_sk</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct inet_timewait_death_row tcp_death_row</code> ➡️ <code>struct inet_timewait_death_row * tcp_death_row</code>
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
<code>struct udp_table * udp_table</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sysctl_tcp_child_ehash_entries</code>
</li>
<li>
<b>Field added. </b>
<code>u32 tcp_challenge_timestamp</code>
</li>
<li>
<b>Field added. </b>
<code>u32 tcp_challenge_count</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_plb_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_plb_idle_rehash_rounds</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_plb_rehash_rounds</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_plb_suspend_rto_sec</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_tcp_plb_cong_thresh</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sysctl_udp_child_hash_entries</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct inet_timewait_death_row * tcp_death_row</code> ➡️ <code>struct inet_timewait_death_row tcp_death_row</code>
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
<code>u8 sysctl_tcp_shrink_window</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_syn_linear_timeouts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__netns_ipv4_read_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__netns_ipv4_read_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__netns_ipv4_read_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__netns_ipv4_read_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__netns_ipv4_read_rx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__netns_ipv4_read_rx</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_backlog_ack_defer</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sysctl_tcp_pingpong_thresh</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mr_table * mrt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head mr_tables</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fib_rules_ops * mr_rules_ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mr_table * mrt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head mr_tables</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fib_rules_ops * mr_rules_ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mr_table * mrt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head mr_tables</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fib_rules_ops * mr_rules_ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
