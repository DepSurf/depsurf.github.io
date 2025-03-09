# Struct: <code>net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net {
    atomic_t passive;
    atomic_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head cleanup_list;
    struct list_head exit_list;
    struct user_namespace * user_ns;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct net {
    atomic_t passive;
    atomic_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head cleanup_list;
    struct list_head exit_list;
    struct user_namespace * user_ns;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct net {
    atomic_t passive;
    atomic_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head cleanup_list;
    struct list_head exit_list;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    atomic_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head cleanup_list;
    struct list_head exit_list;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    atomic_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head cleanup_list;
    struct list_head exit_list;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct list_head fib_notifier_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct list_head fib_notifier_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    atomic64_t cookie_gen;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct list_head fib_notifier_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    u32 hash_mix;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    spinlock_t nsid_lock;
    struct idr netns_ids;
    struct ns_common ns;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct list_head dev_base_head;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    unsigned int dev_base_seq;
    int ifindex;
    unsigned int dev_unreg_count;
    struct list_head rules_ops;
    struct list_head fib_notifier_ops;
    struct net_device * loopback_dev;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * diag_nlsk;
    atomic_t fnhe_genid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    atomic64_t net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    atomic64_t net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    u64 net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
    struct netns_smc smc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_nf nf;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    u64 net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct netns_mctp mctp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
    struct netns_smc smc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    atomic_t dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct ref_tracker_dir refcnt_tracker;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_nf nf;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    u64 net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct netns_mctp mctp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
    struct netns_smc smc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    atomic_t dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct ref_tracker_dir refcnt_tracker;
    struct ref_tracker_dir notrefcnt_tracker;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_nf nf;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_ft ft;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    u64 net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct netns_mctp mctp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
    struct netns_smc smc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    atomic_t dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct ref_tracker_dir refcnt_tracker;
    struct ref_tracker_dir notrefcnt_tracker;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_nf nf;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_ft ft;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    u64 net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct netns_mctp mctp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
    struct netns_smc smc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    spinlock_t rules_mod_lock;
    atomic_t dev_unreg_count;
    unsigned int dev_base_seq;
    u32 ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct ref_tracker_dir refcnt_tracker;
    struct ref_tracker_dir notrefcnt_tracker;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    struct xarray dev_by_index;
    struct raw_notifier_head netdev_chain;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_nf nf;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_ft ft;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct netns_bpf bpf;
    struct netns_xfrm xfrm;
    u64 net_cookie;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct netns_mctp mctp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
    struct netns_smc smc;
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
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
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
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net {
    refcount_t passive;
    refcount_t count;
    spinlock_t rules_mod_lock;
    unsigned int dev_unreg_count;
    unsigned int dev_base_seq;
    int ifindex;
    spinlock_t nsid_lock;
    atomic_t fnhe_genid;
    struct list_head list;
    struct list_head exit_list;
    struct llist_node cleanup_list;
    struct key_tag * key_domain;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct idr netns_ids;
    struct ns_common ns;
    struct list_head dev_base_head;
    struct proc_dir_entry * proc_net;
    struct proc_dir_entry * proc_net_stat;
    struct ctl_table_set sysctls;
    struct sock * rtnl;
    struct sock * genl_sock;
    struct uevent_sock * uevent_sock;
    struct hlist_head * dev_name_head;
    struct hlist_head * dev_index_head;
    u32 hash_mix;
    struct net_device * loopback_dev;
    struct list_head rules_ops;
    struct netns_core core;
    struct netns_mib mib;
    struct netns_packet packet;
    struct netns_unix unx;
    struct netns_nexthop nexthop;
    struct netns_ipv4 ipv4;
    struct netns_ipv6 ipv6;
    struct netns_ieee802154_lowpan ieee802154_lowpan;
    struct netns_sctp sctp;
    struct netns_dccp dccp;
    struct netns_nf nf;
    struct netns_xt xt;
    struct netns_ct ct;
    struct netns_nftables nft;
    struct netns_nf_frag nf_frag;
    struct ctl_table_header * nf_frag_frags_hdr;
    struct sock * nfnl;
    struct sock * nfnl_stash;
    struct list_head nfnl_acct_list;
    struct list_head nfct_timeout_list;
    struct sk_buff_head wext_nlevents;
    struct net_generic * gen;
    struct bpf_prog * flow_dissector_prog;
    struct netns_xfrm xfrm;
    struct netns_ipvs * ipvs;
    struct netns_mpls mpls;
    struct netns_can can;
    struct netns_xdp xdp;
    struct sock * crypto_nlsk;
    struct sock * diag_nlsk;
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
<code>struct list_head nfct_timeout_list</code>
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
<code>struct ucounts * ucounts</code>
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
<code>struct netns_can can</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t passive</code> ➡️ <code>refcount_t passive</code>
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
<code>struct list_head fib_notifier_ops</code>
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
<code>struct uevent_sock * uevent_sock</code>
</li>
<li>
<b>Field added. </b>
<code>struct ctl_table_header * nf_frag_frags_hdr</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t count</code> ➡️ <code>refcount_t count</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head cleanup_list</code> ➡️ <code>struct llist_node cleanup_list</code>
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
<code>struct bpf_prog * flow_dissector_prog</code>
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
<code>u32 hash_mix</code>
</li>
<li>
<b>Field added. </b>
<code>struct key_tag * key_domain</code>
</li>
<li>
<b>Field added. </b>
<code>struct netns_nexthop nexthop</code>
</li>
<li>
<b>Field added. </b>
<code>struct netns_xdp xdp</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic64_t cookie_gen</code>
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
<code>struct sock * crypto_nlsk</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head fib_notifier_ops</code>
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
<code>struct raw_notifier_head netdev_chain</code>
</li>
<li>
<b>Field added. </b>
<code>struct netns_bpf bpf</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t net_cookie</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_prog * flow_dissector_prog</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>refcount_t count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head nfnl_acct_list</code>
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
<code>struct netns_smc smc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netns_dccp dccp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netns_nf_frag nf_frag</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ctl_table_header * nf_frag_frags_hdr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * nfnl</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * nfnl_stash</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head nfct_timeout_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic64_t net_cookie</code> ➡️ <code>u64 net_cookie</code>
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
<code>struct netns_mctp mctp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netns_xt xt</code>
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
<code>struct ref_tracker_dir refcnt_tracker</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int dev_unreg_count</code> ➡️ <code>atomic_t dev_unreg_count</code>
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
<code>struct ref_tracker_dir notrefcnt_tracker</code>
</li>
<li>
<b>Field added. </b>
<code>struct netns_ft ft</code>
</li>
</ul>
</details>
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
<code>struct xarray dev_by_index</code>
</li>
<li>
<b>Field type changed. </b>
<code>int ifindex</code> ➡️ <code>u32 ifindex</code>
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
