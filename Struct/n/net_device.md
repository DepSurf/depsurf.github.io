# Struct: <code>net_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    char * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    atomic_t carrier_changes;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    struct (anon) all_adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    long unsigned int last_rx;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct tcf_proto * ingress_cl_list;
    struct netdev_queue * ingress_queue;
    struct list_head nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    long unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_maps;
    long unsigned int trans_start;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    void (*)(struct net_device *) destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct pcpu_vstats * vstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    u16 gso_min_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct lock_class_key * qdisc_tx_busylock;
    bool proto_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    char * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    atomic_t carrier_changes;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    struct (anon) all_adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct switchdev_ops * switchdev_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_switch_tree * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    long unsigned int last_rx;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct tcf_proto * ingress_cl_list;
    struct netdev_queue * ingress_queue;
    struct list_head nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    long unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_maps;
    struct tcf_proto * egress_cl_list;
    u32 offload_fwd_mark;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    void (*)(struct net_device *) destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct pcpu_vstats * vstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    char * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    atomic_t carrier_changes;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct switchdev_ops * switchdev_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    short unsigned int min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_switch_tree * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    long unsigned int last_rx;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct tcf_proto * ingress_cl_list;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entry * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    long unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_maps;
    struct tcf_proto * egress_cl_list;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    void (*)(struct net_device *) destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct pcpu_vstats * vstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    char * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    atomic_t carrier_changes;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct switchdev_ops * switchdev_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_switch_tree * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct tcf_proto * ingress_cl_list;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entry * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_maps;
    struct tcf_proto * egress_cl_list;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct pcpu_vstats * vstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    atomic_t carrier_changes;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct switchdev_ops * switchdev_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct pcpu_vstats * vstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct switchdev_ops * switchdev_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct pcpu_vstats * vstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct switchdev_ops * switchdev_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
    unsigned int wol_enabled;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
    unsigned int wol_enabled;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    unsigned int flags;
    unsigned int priv_flags;
    const struct net_device_ops * netdev_ops;
    int ifindex;
    short unsigned int gflags;
    short unsigned int hard_header_len;
    unsigned int mtu;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    short unsigned int padded;
    spinlock_t addr_list_lock;
    int irq;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps *[2] xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
    unsigned int wol_enabled;
    unsigned int threaded;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    unsigned int flags;
    unsigned int priv_flags;
    const struct net_device_ops * netdev_ops;
    int ifindex;
    short unsigned int gflags;
    short unsigned int hard_header_len;
    unsigned int mtu;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    short unsigned int padded;
    spinlock_t addr_list_lock;
    int irq;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    struct mctp_dev * mctp_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps *[2] xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    struct lock_class_key * qdisc_running_key;
    bool proto_down;
    unsigned int wol_enabled;
    unsigned int threaded;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    unsigned int flags;
    long long unsigned int priv_flags;
    const struct net_device_ops * netdev_ops;
    int ifindex;
    short unsigned int gflags;
    short unsigned int hard_header_len;
    unsigned int mtu;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    int group;
    struct net_device_stats stats;
    struct net_device_core_stats * core_stats;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    short unsigned int padded;
    spinlock_t addr_list_lock;
    int irq;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct in_device * ip_ptr;
    struct inet6_dev * ip6_ptr;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct dn_dev * dn_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    struct mctp_dev * mctp_ptr;
    const unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    unsigned int gro_max_size;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps *[2] xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct nf_hook_entries * nf_hooks_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct ref_tracker_dir refcnt_tracker;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct dm_hw_stat_delta * dm_private;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    unsigned int tso_max_size;
    u16 gso_max_segs;
    u16 tso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    bool proto_down;
    unsigned int wol_enabled;
    unsigned int threaded;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
    u8[32] dev_addr_shadow;
    netdevice_tracker linkwatch_dev_tracker;
    netdevice_tracker watchdog_dev_tracker;
    netdevice_tracker dev_registered_tracker;
    struct rtnl_hw_stats64 * offload_xstats_l3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    unsigned int flags;
    long long unsigned int priv_flags;
    const struct net_device_ops * netdev_ops;
    int ifindex;
    short unsigned int gflags;
    short unsigned int hard_header_len;
    unsigned int mtu;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    int group;
    struct net_device_stats stats;
    struct net_device_core_stats * core_stats;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    short unsigned int padded;
    spinlock_t addr_list_lock;
    int irq;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct in_device * ip_ptr;
    struct inet6_dev * ip6_ptr;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    struct mctp_dev * mctp_ptr;
    const unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    unsigned int gro_max_size;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps *[2] xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct nf_hook_entries * nf_hooks_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct ref_tracker_dir refcnt_tracker;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct dm_hw_stat_delta * dm_private;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    unsigned int tso_max_size;
    u16 gso_max_segs;
    u16 tso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    bool proto_down;
    unsigned int wol_enabled;
    unsigned int threaded;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
    u8[32] dev_addr_shadow;
    netdevice_tracker linkwatch_dev_tracker;
    netdevice_tracker watchdog_dev_tracker;
    netdevice_tracker dev_registered_tracker;
    struct rtnl_hw_stats64 * offload_xstats_l3;
    struct devlink_port * devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    unsigned int flags;
    xdp_features_t xdp_features;
    long long unsigned int priv_flags;
    const struct net_device_ops * netdev_ops;
    const struct xdp_metadata_ops * xdp_metadata_ops;
    int ifindex;
    short unsigned int gflags;
    short unsigned int hard_header_len;
    unsigned int mtu;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    int group;
    struct net_device_stats stats;
    struct net_device_core_stats * core_stats;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    short unsigned int padded;
    spinlock_t addr_list_lock;
    int irq;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct in_device * ip_ptr;
    struct inet6_dev * ip6_ptr;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    struct mctp_dev * mctp_ptr;
    const unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    unsigned int gro_max_size;
    unsigned int gro_ipv4_max_size;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct xps_dev_maps *[2] xps_maps;
    struct mini_Qdisc * miniq_egress;
    struct nf_hook_entries * nf_hooks_egress;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct ref_tracker_dir refcnt_tracker;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct dm_hw_stat_delta * dm_private;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    unsigned int tso_max_size;
    u16 gso_max_segs;
    u16 tso_max_segs;
    unsigned int gso_ipv4_max_size;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    bool proto_down;
    unsigned int wol_enabled;
    unsigned int threaded;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
    u8[32] dev_addr_shadow;
    netdevice_tracker linkwatch_dev_tracker;
    netdevice_tracker watchdog_dev_tracker;
    netdevice_tracker dev_registered_tracker;
    struct rtnl_hw_stats64 * offload_xstats_l3;
    struct devlink_port * devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_device {
    __u8[0] __cacheline_group_begin__net_device_read_tx;
    long long unsigned int priv_flags;
    const struct net_device_ops * netdev_ops;
    const struct header_ops * header_ops;
    struct netdev_queue * _tx;
    netdev_features_t gso_partial_features;
    unsigned int real_num_tx_queues;
    unsigned int gso_max_size;
    unsigned int gso_ipv4_max_size;
    u16 gso_max_segs;
    s16 num_tc;
    unsigned int mtu;
    short unsigned int needed_headroom;
    struct netdev_tc_txq[16] tc_to_txq;
    struct xps_dev_maps *[2] xps_maps;
    struct nf_hook_entries * nf_hooks_egress;
    struct bpf_mprog_entry * tcx_egress;
    __u8[0] __cacheline_group_end__net_device_read_tx;
    __u8[0] __cacheline_group_begin__net_device_read_txrx;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    unsigned int flags;
    short unsigned int hard_header_len;
    netdev_features_t features;
    struct inet6_dev * ip6_ptr;
    __u8[0] __cacheline_group_end__net_device_read_txrx;
    __u8[0] __cacheline_group_begin__net_device_read_rx;
    struct bpf_prog * xdp_prog;
    struct list_head ptype_specific;
    int ifindex;
    unsigned int real_num_rx_queues;
    struct netdev_rx_queue * _rx;
    long unsigned int gro_flush_timeout;
    int napi_defer_hard_irqs;
    unsigned int gro_max_size;
    unsigned int gro_ipv4_max_size;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    possible_net_t nd_net;
    struct netpoll_info * npinfo;
    struct bpf_mprog_entry * tcx_ingress;
    __u8[0] __cacheline_group_end__net_device_read_rx;
    char[16] name;
    struct netdev_name_node * name_node;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct (anon) adj_list;
    xdp_features_t xdp_features;
    const struct xdp_metadata_ops * xdp_metadata_ops;
    const struct xsk_tx_metadata_ops * xsk_tx_metadata_ops;
    short unsigned int gflags;
    short unsigned int needed_tailroom;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    unsigned char min_header_len;
    unsigned char name_assign_type;
    int group;
    struct net_device_stats stats;
    struct net_device_core_stats * core_stats;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    short unsigned int padded;
    spinlock_t addr_list_lock;
    int irq;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    bool uc_promisc;
    struct in_device * ip_ptr;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    struct mctp_dev * mctp_ptr;
    const unsigned char * dev_addr;
    unsigned int num_rx_queues;
    unsigned int xdp_zc_max_segs;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    unsigned int num_tx_queues;
    struct Qdisc * qdisc;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    struct xdp_dev_bulk_queue * xdp_bulkq;
    struct hlist_head[16] qdisc_hash;
    struct timer_list watchdog_timer;
    int watchdog_timeo;
    u32 proto_down_reason;
    struct list_head todo_list;
    int * pcpu_refcnt;
    struct ref_tracker_dir refcnt_tracker;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    void * ml_priv;
    enum netdev_ml_priv_type ml_priv_type;
    enum netdev_stat_type pcpu_stat_type;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct dm_hw_stat_delta * dm_private;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int tso_max_size;
    u16 tso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key * qdisc_tx_busylock;
    bool proto_down;
    unsigned int wol_enabled;
    unsigned int threaded;
    struct list_head net_notifier_list;
    const struct macsec_ops * macsec_ops;
    const struct udp_tunnel_nic_info * udp_tunnel_nic_info;
    struct udp_tunnel_nic * udp_tunnel_nic;
    struct bpf_xdp_entity[3] xdp_state;
    u8[32] dev_addr_shadow;
    netdevice_tracker linkwatch_dev_tracker;
    netdevice_tracker watchdog_dev_tracker;
    netdevice_tracker dev_registered_tracker;
    struct rtnl_hw_stats64 * offload_xstats_l3;
    struct devlink_port * devlink_port;
    struct dpll_pin * dpll_pin;
    struct hlist_head page_pools;
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
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
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
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net_device {
    char[16] name;
    struct hlist_node name_hlist;
    struct dev_ifalias * ifalias;
    long unsigned int mem_end;
    long unsigned int mem_start;
    long unsigned int base_addr;
    int irq;
    long unsigned int state;
    struct list_head dev_list;
    struct list_head napi_list;
    struct list_head unreg_list;
    struct list_head close_list;
    struct list_head ptype_all;
    struct list_head ptype_specific;
    struct (anon) adj_list;
    netdev_features_t features;
    netdev_features_t hw_features;
    netdev_features_t wanted_features;
    netdev_features_t vlan_features;
    netdev_features_t hw_enc_features;
    netdev_features_t mpls_features;
    netdev_features_t gso_partial_features;
    int ifindex;
    int group;
    struct net_device_stats stats;
    atomic_long_t rx_dropped;
    atomic_long_t tx_dropped;
    atomic_long_t rx_nohandler;
    atomic_t carrier_up_count;
    atomic_t carrier_down_count;
    const struct iw_handler_def * wireless_handlers;
    struct iw_public_data * wireless_data;
    const struct net_device_ops * netdev_ops;
    const struct ethtool_ops * ethtool_ops;
    const struct l3mdev_ops * l3mdev_ops;
    const struct ndisc_ops * ndisc_ops;
    const struct xfrmdev_ops * xfrmdev_ops;
    const struct tlsdev_ops * tlsdev_ops;
    const struct header_ops * header_ops;
    unsigned int flags;
    unsigned int priv_flags;
    short unsigned int gflags;
    short unsigned int padded;
    unsigned char operstate;
    unsigned char link_mode;
    unsigned char if_port;
    unsigned char dma;
    unsigned int mtu;
    unsigned int min_mtu;
    unsigned int max_mtu;
    short unsigned int type;
    short unsigned int hard_header_len;
    unsigned char min_header_len;
    short unsigned int needed_headroom;
    short unsigned int needed_tailroom;
    unsigned char[32] perm_addr;
    unsigned char addr_assign_type;
    unsigned char addr_len;
    unsigned char upper_level;
    unsigned char lower_level;
    short unsigned int neigh_priv_len;
    short unsigned int dev_id;
    short unsigned int dev_port;
    spinlock_t addr_list_lock;
    unsigned char name_assign_type;
    bool uc_promisc;
    struct netdev_hw_addr_list uc;
    struct netdev_hw_addr_list mc;
    struct netdev_hw_addr_list dev_addrs;
    struct kset * queues_kset;
    unsigned int promiscuity;
    unsigned int allmulti;
    struct vlan_info * vlan_info;
    struct dsa_port * dsa_ptr;
    struct tipc_bearer * tipc_ptr;
    void * atalk_ptr;
    struct in_device * ip_ptr;
    struct dn_dev * dn_ptr;
    struct inet6_dev * ip6_ptr;
    void * ax25_ptr;
    struct wireless_dev * ieee80211_ptr;
    struct wpan_dev * ieee802154_ptr;
    struct mpls_dev * mpls_ptr;
    unsigned char * dev_addr;
    struct netdev_rx_queue * _rx;
    unsigned int num_rx_queues;
    unsigned int real_num_rx_queues;
    struct bpf_prog * xdp_prog;
    long unsigned int gro_flush_timeout;
    rx_handler_func_t * rx_handler;
    void * rx_handler_data;
    struct mini_Qdisc * miniq_ingress;
    struct netdev_queue * ingress_queue;
    struct nf_hook_entries * nf_hooks_ingress;
    unsigned char[32] broadcast;
    struct cpu_rmap * rx_cpu_rmap;
    struct hlist_node index_hlist;
    struct netdev_queue * _tx;
    unsigned int num_tx_queues;
    unsigned int real_num_tx_queues;
    struct Qdisc * qdisc;
    struct hlist_head[16] qdisc_hash;
    unsigned int tx_queue_len;
    spinlock_t tx_global_lock;
    int watchdog_timeo;
    struct xps_dev_maps * xps_cpus_map;
    struct xps_dev_maps * xps_rxqs_map;
    struct mini_Qdisc * miniq_egress;
    struct timer_list watchdog_timer;
    int * pcpu_refcnt;
    struct list_head todo_list;
    struct list_head link_watch_list;
    enum (anon) reg_state;
    bool dismantle;
    enum (anon) rtnl_link_state;
    bool needs_free_netdev;
    void (*)(struct net_device *) priv_destructor;
    struct netpoll_info * npinfo;
    possible_net_t nd_net;
    void * ml_priv;
    struct pcpu_lstats * lstats;
    struct pcpu_sw_netstats * tstats;
    struct pcpu_dstats * dstats;
    struct garp_port * garp_port;
    struct mrp_port * mrp_port;
    struct device dev;
    const struct attribute_group *[4] sysfs_groups;
    const struct attribute_group * sysfs_rx_queue_group;
    const struct rtnl_link_ops * rtnl_link_ops;
    unsigned int gso_max_size;
    u16 gso_max_segs;
    const struct dcbnl_rtnl_ops * dcbnl_ops;
    s16 num_tc;
    struct netdev_tc_txq[16] tc_to_txq;
    u8[16] prio_tc_map;
    unsigned int fcoe_ddp_xid;
    struct netprio_map * priomap;
    struct phy_device * phydev;
    struct sfp_bus * sfp_bus;
    struct lock_class_key qdisc_tx_busylock_key;
    struct lock_class_key qdisc_running_key;
    struct lock_class_key qdisc_xmit_lock_key;
    struct lock_class_key addr_list_lock_key;
    bool proto_down;
    unsigned int wol_enabled;
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
<code>netdev_features_t gso_partial_features</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t rx_nohandler</code>
</li>
<li>
<b>Field added. </b>
<code>const struct switchdev_ops * switchdev_ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct ndisc_ops * ndisc_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct dsa_switch_tree * dsa_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>struct tcf_proto * egress_cl_list</code>
</li>
<li>
<b>Field added. </b>
<code>u32 offload_fwd_mark</code>
</li>
<li>
<b>Field added. </b>
<code>struct lock_class_key * qdisc_running_key</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int trans_start</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 gso_min_segs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct wpan_dev * ieee802154_ptr</code> ➡️ <code>struct wpan_dev * ieee802154_ptr</code>
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
<code>unsigned int min_mtu</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_mtu</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int min_header_len</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head[16] qdisc_hash</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) all_adj_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 offload_fwd_mark</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head nf_hooks_ingress</code> ➡️ <code>struct nf_hook_entry * nf_hooks_ingress</code>
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
<code>const struct xfrmdev_ops * xfrmdev_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog * xdp_prog</code>
</li>
<li>
<b>Field added. </b>
<code>bool needs_free_netdev</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *) priv_destructor</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_rx</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *) destructor</code>
</li>
<li>
<b>Field type changed. </b>
<code>short unsigned int min_header_len</code> ➡️ <code>unsigned char min_header_len</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int tx_queue_len</code> ➡️ <code>unsigned int tx_queue_len</code>
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
<code>struct mini_Qdisc * miniq_ingress</code>
</li>
<li>
<b>Field added. </b>
<code>struct mini_Qdisc * miniq_egress</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tcf_proto * ingress_cl_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tcf_proto * egress_cl_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>char * ifalias</code> ➡️ <code>struct dev_ifalias * ifalias</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dsa_switch_tree * dsa_ptr</code> ➡️ <code>struct dsa_port * dsa_ptr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct nf_hook_entry * nf_hooks_ingress</code> ➡️ <code>struct nf_hook_entries * nf_hooks_ingress</code>
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
<code>atomic_t carrier_up_count</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t carrier_down_count</code>
</li>
<li>
<b>Field added. </b>
<code>const struct tlsdev_ops * tlsdev_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct sfp_bus * sfp_bus</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t carrier_changes</code>
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
<code>struct xps_dev_maps * xps_cpus_map</code>
</li>
<li>
<b>Field added. </b>
<code>struct xps_dev_maps * xps_rxqs_map</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int wol_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xps_dev_maps * xps_maps</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pcpu_vstats * vstats</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 num_tc</code> ➡️ <code>s16 num_tc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const struct switchdev_ops * switchdev_ops</code>
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
<code>unsigned char upper_level</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char lower_level</code>
</li>
<li>
<b>Field added. </b>
<code>struct lock_class_key qdisc_tx_busylock_key</code>
</li>
<li>
<b>Field added. </b>
<code>struct lock_class_key qdisc_xmit_lock_key</code>
</li>
<li>
<b>Field added. </b>
<code>struct lock_class_key addr_list_lock_key</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key * qdisc_tx_busylock</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct lock_class_key * qdisc_running_key</code> ➡️ <code>struct lock_class_key qdisc_running_key</code>
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
<code>struct netdev_name_node * name_node</code>
</li>
<li>
<b>Field added. </b>
<code>int napi_defer_hard_irqs</code>
</li>
<li>
<b>Field added. </b>
<code>struct xdp_dev_bulk_queue * xdp_bulkq</code>
</li>
<li>
<b>Field added. </b>
<code>struct lock_class_key * qdisc_tx_busylock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head net_notifier_list</code>
</li>
<li>
<b>Field added. </b>
<code>const struct macsec_ops * macsec_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node name_hlist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key qdisc_tx_busylock_key</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key qdisc_xmit_lock_key</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key addr_list_lock_key</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct lock_class_key qdisc_running_key</code> ➡️ <code>struct lock_class_key * qdisc_running_key</code>
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
<code>u32 proto_down_reason</code>
</li>
<li>
<b>Field added. </b>
<code>enum netdev_ml_priv_type ml_priv_type</code>
</li>
<li>
<b>Field added. </b>
<code>const struct udp_tunnel_nic_info * udp_tunnel_nic_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct udp_tunnel_nic * udp_tunnel_nic</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_xdp_entity[3] xdp_state</code>
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
<code>struct xps_dev_maps *[2] xps_maps</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int threaded</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xps_dev_maps * xps_cpus_map</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xps_dev_maps * xps_rxqs_map</code>
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
<code>struct mctp_dev * mctp_ptr</code>
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
<code>struct net_device_core_stats * core_stats</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int gro_max_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct nf_hook_entries * nf_hooks_egress</code>
</li>
<li>
<b>Field added. </b>
<code>struct ref_tracker_dir refcnt_tracker</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_hw_stat_delta * dm_private</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int tso_max_size</code>
</li>
<li>
<b>Field added. </b>
<code>u16 tso_max_segs</code>
</li>
<li>
<b>Field added. </b>
<code>u8[32] dev_addr_shadow</code>
</li>
<li>
<b>Field added. </b>
<code>netdevice_tracker linkwatch_dev_tracker</code>
</li>
<li>
<b>Field added. </b>
<code>netdevice_tracker watchdog_dev_tracker</code>
</li>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_registered_tracker</code>
</li>
<li>
<b>Field added. </b>
<code>struct rtnl_hw_stats64 * offload_xstats_l3</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t rx_dropped</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t tx_dropped</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t rx_nohandler</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key * qdisc_running_key</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int priv_flags</code> ➡️ <code>long long unsigned int priv_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct mctp_dev * mctp_ptr</code> ➡️ <code>struct mctp_dev * mctp_ptr</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char * dev_addr</code> ➡️ <code>const unsigned char * dev_addr</code>
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
<code>struct devlink_port * devlink_port</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dn_dev * dn_ptr</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct macsec_ops * macsec_ops</code> ➡️ <code>const struct macsec_ops * macsec_ops</code>
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
<code>xdp_features_t xdp_features</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xdp_metadata_ops * xdp_metadata_ops</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int gro_ipv4_max_size</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int gso_ipv4_max_size</code>
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
<code>__u8[0] __cacheline_group_begin__net_device_read_tx</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_mprog_entry * tcx_egress</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__net_device_read_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__net_device_read_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__net_device_read_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__net_device_read_rx</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_mprog_entry * tcx_ingress</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__net_device_read_rx</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xsk_tx_metadata_ops * xsk_tx_metadata_ops</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int xdp_zc_max_segs</code>
</li>
<li>
<b>Field added. </b>
<code>enum netdev_stat_type pcpu_stat_type</code>
</li>
<li>
<b>Field added. </b>
<code>struct dpll_pin * dpll_pin</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head page_pools</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mini_Qdisc * miniq_ingress</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mini_Qdisc * miniq_egress</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct pcpu_dstats * dstats</code> ➡️ <code>struct pcpu_dstats * dstats</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const struct iw_handler_def * wireless_handlers</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iw_public_data * wireless_data</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int fcoe_ddp_xid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
