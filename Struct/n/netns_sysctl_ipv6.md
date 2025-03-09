# Struct: <code>netns_sysctl_ipv6</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    u8 bindv6only;
    u8 multipath_hash_policy;
    u8 flowlabel_consistency;
    u8 auto_flowlabels;
    int icmpv6_time;
    u8 icmpv6_echo_ignore_all;
    u8 icmpv6_echo_ignore_multicast;
    u8 icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    u8 anycast_src_echo_reply;
    u8 ip_nonlocal_bind;
    u8 fwmark_reflect;
    u8 flowlabel_state_ranges;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
    u8 fib_notify_on_flag_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    u32 multipath_hash_fields;
    u8 multipath_hash_policy;
    u8 bindv6only;
    u8 flowlabel_consistency;
    u8 auto_flowlabels;
    int icmpv6_time;
    u8 icmpv6_echo_ignore_all;
    u8 icmpv6_echo_ignore_multicast;
    u8 icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    u8 anycast_src_echo_reply;
    u8 ip_nonlocal_bind;
    u8 fwmark_reflect;
    u8 flowlabel_state_ranges;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    u32 ioam6_id;
    u64 ioam6_id_wide;
    bool skip_notify_on_dev_down;
    u8 fib_notify_on_flag_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    u32 multipath_hash_fields;
    u8 multipath_hash_policy;
    u8 bindv6only;
    u8 flowlabel_consistency;
    u8 auto_flowlabels;
    int icmpv6_time;
    u8 icmpv6_echo_ignore_all;
    u8 icmpv6_echo_ignore_multicast;
    u8 icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    u8 anycast_src_echo_reply;
    u8 ip_nonlocal_bind;
    u8 fwmark_reflect;
    u8 flowlabel_state_ranges;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    u32 ioam6_id;
    u64 ioam6_id_wide;
    bool skip_notify_on_dev_down;
    u8 fib_notify_on_flag_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    u32 multipath_hash_fields;
    u8 multipath_hash_policy;
    u8 bindv6only;
    u8 flowlabel_consistency;
    u8 auto_flowlabels;
    int icmpv6_time;
    u8 icmpv6_echo_ignore_all;
    u8 icmpv6_echo_ignore_multicast;
    u8 icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    u8 anycast_src_echo_reply;
    u8 ip_nonlocal_bind;
    u8 fwmark_reflect;
    u8 flowlabel_state_ranges;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    u32 ioam6_id;
    u64 ioam6_id_wide;
    bool skip_notify_on_dev_down;
    u8 fib_notify_on_flag_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    u32 multipath_hash_fields;
    u8 multipath_hash_policy;
    u8 bindv6only;
    u8 flowlabel_consistency;
    u8 auto_flowlabels;
    int icmpv6_time;
    u8 icmpv6_echo_ignore_all;
    u8 icmpv6_echo_ignore_multicast;
    u8 icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    u8 anycast_src_echo_reply;
    u8 ip_nonlocal_bind;
    u8 fwmark_reflect;
    u8 flowlabel_state_ranges;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    u32 ioam6_id;
    u64 ioam6_id_wide;
    u8 skip_notify_on_dev_down;
    u8 fib_notify_on_flag_change;
    u8 icmpv6_error_anycast_as_unicast;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    u32 multipath_hash_fields;
    u8 multipath_hash_policy;
    u8 bindv6only;
    u8 flowlabel_consistency;
    u8 auto_flowlabels;
    int icmpv6_time;
    u8 icmpv6_echo_ignore_all;
    u8 icmpv6_echo_ignore_multicast;
    u8 icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    u8 anycast_src_echo_reply;
    u8 ip_nonlocal_bind;
    u8 fwmark_reflect;
    u8 flowlabel_state_ranges;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    u32 ioam6_id;
    u64 ioam6_id_wide;
    u8 skip_notify_on_dev_down;
    u8 fib_notify_on_flag_change;
    u8 icmpv6_error_anycast_as_unicast;
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
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[8] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
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
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netns_sysctl_ipv6 {
    struct ctl_table_header * hdr;
    struct ctl_table_header * route_hdr;
    struct ctl_table_header * icmp_hdr;
    struct ctl_table_header * frags_hdr;
    struct ctl_table_header * xfrm6_hdr;
    int bindv6only;
    int flush_delay;
    int ip6_rt_max_size;
    int ip6_rt_gc_min_interval;
    int ip6_rt_gc_timeout;
    int ip6_rt_gc_interval;
    int ip6_rt_gc_elasticity;
    int ip6_rt_mtu_expires;
    int ip6_rt_min_advmss;
    int multipath_hash_policy;
    int flowlabel_consistency;
    int auto_flowlabels;
    int icmpv6_time;
    int icmpv6_echo_ignore_all;
    int icmpv6_echo_ignore_multicast;
    int icmpv6_echo_ignore_anycast;
    long unsigned int[4] icmpv6_ratemask;
    long unsigned int * icmpv6_ratemask_ptr;
    int anycast_src_echo_reply;
    int ip_nonlocal_bind;
    int fwmark_reflect;
    int idgen_retries;
    int idgen_delay;
    int flowlabel_state_ranges;
    int flowlabel_reflect;
    int max_dst_opts_cnt;
    int max_hbh_opts_cnt;
    int max_dst_opts_len;
    int max_hbh_opts_len;
    int seg6_flowlabel;
    bool skip_notify_on_dev_down;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int flowlabel_reflect</code>
</li>
<li>
<b>Field added. </b>
<code>int max_dst_opts_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>int max_hbh_opts_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>int max_dst_opts_len</code>
</li>
<li>
<b>Field added. </b>
<code>int max_hbh_opts_len</code>
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
<code>int multipath_hash_policy</code>
</li>
<li>
<b>Field added. </b>
<code>int seg6_flowlabel</code>
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
<code>int icmpv6_echo_ignore_all</code>
</li>
<li>
<b>Field added. </b>
<code>bool skip_notify_on_dev_down</code>
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
<code>int icmpv6_echo_ignore_multicast</code>
</li>
<li>
<b>Field added. </b>
<code>int icmpv6_echo_ignore_anycast</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[4] icmpv6_ratemask</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * icmpv6_ratemask_ptr</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>u8 fib_notify_on_flag_change</code>
</li>
<li>
<b>Field type changed. </b>
<code>int bindv6only</code> ➡️ <code>u8 bindv6only</code>
</li>
<li>
<b>Field type changed. </b>
<code>int multipath_hash_policy</code> ➡️ <code>u8 multipath_hash_policy</code>
</li>
<li>
<b>Field type changed. </b>
<code>int flowlabel_consistency</code> ➡️ <code>u8 flowlabel_consistency</code>
</li>
<li>
<b>Field type changed. </b>
<code>int auto_flowlabels</code> ➡️ <code>u8 auto_flowlabels</code>
</li>
<li>
<b>Field type changed. </b>
<code>int icmpv6_echo_ignore_all</code> ➡️ <code>u8 icmpv6_echo_ignore_all</code>
</li>
<li>
<b>Field type changed. </b>
<code>int icmpv6_echo_ignore_multicast</code> ➡️ <code>u8 icmpv6_echo_ignore_multicast</code>
</li>
<li>
<b>Field type changed. </b>
<code>int icmpv6_echo_ignore_anycast</code> ➡️ <code>u8 icmpv6_echo_ignore_anycast</code>
</li>
<li>
<b>Field type changed. </b>
<code>int anycast_src_echo_reply</code> ➡️ <code>u8 anycast_src_echo_reply</code>
</li>
<li>
<b>Field type changed. </b>
<code>int ip_nonlocal_bind</code> ➡️ <code>u8 ip_nonlocal_bind</code>
</li>
<li>
<b>Field type changed. </b>
<code>int fwmark_reflect</code> ➡️ <code>u8 fwmark_reflect</code>
</li>
<li>
<b>Field type changed. </b>
<code>int flowlabel_state_ranges</code> ➡️ <code>u8 flowlabel_state_ranges</code>
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
<code>u32 multipath_hash_fields</code>
</li>
<li>
<b>Field added. </b>
<code>u32 ioam6_id</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ioam6_id_wide</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 icmpv6_error_anycast_as_unicast</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool skip_notify_on_dev_down</code> ➡️ <code>u8 skip_notify_on_dev_down</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[4] icmpv6_ratemask</code> ➡️ <code>long unsigned int[8] icmpv6_ratemask</code>
</li>
</ul>
</details>
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
