# Struct: <code>net_device_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    struct rtnl_link_stats64 * (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct napi_struct *) ndo_busy_poll;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, u32, __be16, struct tc_to_netdev *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct neighbour *) ndo_neigh_construct;
    void (*)(struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int) ndo_fdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, sa_family_t, __be16) ndo_add_vxlan_port;
    void (*)(struct net_device *, sa_family_t, __be16) ndo_del_vxlan_port;
    void (*)(struct net_device *, sa_family_t, __be16) ndo_add_geneve_port;
    void (*)(struct net_device *, sa_family_t, __be16) ndo_del_geneve_port;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *, void *) ndo_dfwd_start_xmit;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    struct rtnl_link_stats64 * (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct napi_struct *) ndo_busy_poll;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, u32, __be16, struct tc_to_netdev *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int) ndo_fdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *, void *) ndo_dfwd_start_xmit;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_xdp *) ndo_xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    struct rtnl_link_stats64 * (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct napi_struct *) ndo_busy_poll;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, u32, __be16, struct tc_to_netdev *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *, void *) ndo_dfwd_start_xmit;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_xdp *) ndo_xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, u32, u32, __be16, struct tc_to_netdev *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_xdp *) ndo_xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, struct xdp_buff *) ndo_xdp_xmit;
    void (*)(struct net_device *) ndo_xdp_flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32) ndo_xsk_async_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *, select_queue_fallback_t) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32) ndo_xsk_async_xmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *) ndo_get_lock_subclass;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32) ndo_xsk_async_xmit;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
    int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_eth_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_siocbond;
    int (*)(struct net_device *, struct if_settings *) ndo_siocwandev;
    int (*)(struct net_device *, struct ifreq *, void *, int) ndo_siocdevprivate;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    struct net_device * (*)(struct net_device *, struct xdp_buff *) ndo_xdp_get_xmit_slave;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
    int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_eth_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_siocbond;
    int (*)(struct net_device *, struct if_settings *) ndo_siocwandev;
    int (*)(struct net_device *, struct ifreq *, void *, int) ndo_siocdevprivate;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, struct netlink_ext_ack *) ndo_fdb_del;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, u16, struct netlink_ext_ack *) ndo_fdb_del_bulk;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    struct net_device * (*)(struct net_device *, struct xdp_buff *) ndo_xdp_get_xmit_slave;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
    int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path;
    ktime_t (*)(struct net_device *, const struct skb_shared_hwtstamps *, bool) ndo_get_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_eth_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_siocbond;
    int (*)(struct net_device *, struct if_settings *) ndo_siocwandev;
    int (*)(struct net_device *, struct ifreq *, void *, int) ndo_siocdevprivate;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, struct netlink_ext_ack *) ndo_fdb_del;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, u16, struct netlink_ext_ack *) ndo_fdb_del_bulk;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    struct net_device * (*)(struct net_device *, struct xdp_buff *) ndo_xdp_get_xmit_slave;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
    int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path;
    ktime_t (*)(struct net_device *, const struct skb_shared_hwtstamps *, bool) ndo_get_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_eth_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_siocbond;
    int (*)(struct net_device *, struct if_settings *) ndo_siocwandev;
    int (*)(struct net_device *, struct ifreq *, void *, int) ndo_siocdevprivate;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, struct netlink_ext_ack *) ndo_fdb_del;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, u16, struct netlink_ext_ack *) ndo_fdb_del_bulk;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlattr * *, u16, struct netlink_ext_ack *) ndo_mdb_add;
    int (*)(struct net_device *, struct nlattr * *, struct netlink_ext_ack *) ndo_mdb_del;
    int (*)(struct net_device *, struct sk_buff *, struct netlink_callback *) ndo_mdb_dump;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    struct net_device * (*)(struct net_device *, struct xdp_buff *) ndo_xdp_get_xmit_slave;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
    int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path;
    ktime_t (*)(struct net_device *, const struct skb_shared_hwtstamps *, bool) ndo_get_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_eth_ioctl;
    int (*)(struct net_device *, struct ifreq *, int) ndo_siocbond;
    int (*)(struct net_device *, struct if_settings *) ndo_siocwandev;
    int (*)(struct net_device *, struct ifreq *, void *, int) ndo_siocdevprivate;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *, unsigned int) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave;
    struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, struct netlink_ext_ack *) ndo_fdb_del;
    int (*)(struct nlmsghdr *, struct net_device *, struct netlink_ext_ack *) ndo_fdb_del_bulk;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlattr * *, u16, struct netlink_ext_ack *) ndo_mdb_add;
    int (*)(struct net_device *, struct nlattr * *, struct netlink_ext_ack *) ndo_mdb_del;
    int (*)(struct net_device *, struct nlattr * *, struct netlink_ext_ack *) ndo_mdb_del_bulk;
    int (*)(struct net_device *, struct sk_buff *, struct netlink_callback *) ndo_mdb_dump;
    int (*)(struct net_device *, struct nlattr * *, u32, u32, struct netlink_ext_ack *) ndo_mdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    struct net_device * (*)(struct net_device *, struct xdp_buff *) ndo_xdp_get_xmit_slave;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl;
    struct net_device * (*)(struct net_device *) ndo_get_peer_dev;
    int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path;
    ktime_t (*)(struct net_device *, const struct skb_shared_hwtstamps *, bool) ndo_get_tstamp;
    int (*)(struct net_device *, struct kernel_hwtstamp_config *) ndo_hwtstamp_get;
    int (*)(struct net_device *, struct kernel_hwtstamp_config *, struct netlink_ext_ack *) ndo_hwtstamp_set;
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
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
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
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net_device_ops {
    int (*)(struct net_device *) ndo_init;
    void (*)(struct net_device *) ndo_uninit;
    int (*)(struct net_device *) ndo_open;
    int (*)(struct net_device *) ndo_stop;
    netdev_tx_t (*)(struct sk_buff *, struct net_device *) ndo_start_xmit;
    netdev_features_t (*)(struct sk_buff *, struct net_device *, netdev_features_t) ndo_features_check;
    u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue;
    void (*)(struct net_device *, int) ndo_change_rx_flags;
    void (*)(struct net_device *) ndo_set_rx_mode;
    int (*)(struct net_device *, void *) ndo_set_mac_address;
    int (*)(struct net_device *) ndo_validate_addr;
    int (*)(struct net_device *, struct ifreq *, int) ndo_do_ioctl;
    int (*)(struct net_device *, struct ifmap *) ndo_set_config;
    int (*)(struct net_device *, int) ndo_change_mtu;
    int (*)(struct net_device *, struct neigh_parms *) ndo_neigh_setup;
    void (*)(struct net_device *) ndo_tx_timeout;
    void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64;
    bool (*)(const struct net_device *, int) ndo_has_offload_stats;
    int (*)(int, const struct net_device *, void *) ndo_get_offload_stats;
    struct net_device_stats * (*)(struct net_device *) ndo_get_stats;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_add_vid;
    int (*)(struct net_device *, __be16, u16) ndo_vlan_rx_kill_vid;
    void (*)(struct net_device *) ndo_poll_controller;
    int (*)(struct net_device *, struct netpoll_info *) ndo_netpoll_setup;
    void (*)(struct net_device *) ndo_netpoll_cleanup;
    int (*)(struct net_device *, int, u8 *) ndo_set_vf_mac;
    int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan;
    int (*)(struct net_device *, int, int, int) ndo_set_vf_rate;
    int (*)(struct net_device *, int, bool) ndo_set_vf_spoofchk;
    int (*)(struct net_device *, int, bool) ndo_set_vf_trust;
    int (*)(struct net_device *, int, struct ifla_vf_info *) ndo_get_vf_config;
    int (*)(struct net_device *, int, int) ndo_set_vf_link_state;
    int (*)(struct net_device *, int, struct ifla_vf_stats *) ndo_get_vf_stats;
    int (*)(struct net_device *, int, struct nlattr * *) ndo_set_vf_port;
    int (*)(struct net_device *, int, struct sk_buff *) ndo_get_vf_port;
    int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid;
    int (*)(struct net_device *, int, bool) ndo_set_vf_rss_query_en;
    int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc;
    int (*)(struct net_device *) ndo_fcoe_enable;
    int (*)(struct net_device *) ndo_fcoe_disable;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup;
    int (*)(struct net_device *, u16) ndo_fcoe_ddp_done;
    int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target;
    int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo;
    int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn;
    int (*)(struct net_device *, const struct sk_buff *, u16, u32) ndo_rx_flow_steer;
    int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave;
    int (*)(struct net_device *, struct net_device *) ndo_del_slave;
    netdev_features_t (*)(struct net_device *, netdev_features_t) ndo_fix_features;
    int (*)(struct net_device *, netdev_features_t) ndo_set_features;
    int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct;
    void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add;
    int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del;
    int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump;
    int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get;
    int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink;
    int (*)(struct sk_buff *, u32, u32, struct net_device *, u32, int) ndo_bridge_getlink;
    int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_dellink;
    int (*)(struct net_device *, bool) ndo_change_carrier;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_phys_port_id;
    int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id;
    int (*)(struct net_device *, char *, size_t) ndo_get_phys_port_name;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add;
    void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del;
    void * (*)(struct net_device *, struct net_device *) ndo_dfwd_add_station;
    void (*)(struct net_device *, void *) ndo_dfwd_del_station;
    int (*)(struct net_device *, int, u32) ndo_set_tx_maxrate;
    int (*)(const struct net_device *) ndo_get_iflink;
    int (*)(struct net_device *, bool) ndo_change_proto_down;
    int (*)(struct net_device *, struct sk_buff *) ndo_fill_metadata_dst;
    void (*)(struct net_device *, int) ndo_set_rx_headroom;
    int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf;
    int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit;
    int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup;
    struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port;
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
<code>int (*)(struct net_device *, int, u64, int) ndo_set_vf_guid</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *, int) ndo_set_rx_headroom</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct netdev_xdp *) ndo_xdp</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *, sa_family_t, __be16) ndo_add_vxlan_port</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *, sa_family_t, __be16) ndo_del_vxlan_port</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *, sa_family_t, __be16) ndo_add_geneve_port</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *, sa_family_t, __be16) ndo_del_geneve_port</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct neighbour *) ndo_neigh_construct</code> ➡️ <code>int (*)(struct net_device *, struct neighbour *) ndo_neigh_construct</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct neighbour *) ndo_neigh_destroy</code> ➡️ <code>void (*)(struct net_device *, struct neighbour *) ndo_neigh_destroy</code>
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
<code>bool (*)(const struct net_device *, int) ndo_has_offload_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(int, const struct net_device *, void *) ndo_get_offload_stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, int, u16, u8) ndo_set_vf_vlan</code> ➡️ <code>int (*)(struct net_device *, int, u16, u8, __be16) ndo_set_vf_vlan</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int) ndo_fdb_dump</code> ➡️ <code>int (*)(struct sk_buff *, struct netlink_callback *, struct net_device *, struct net_device *, int *) ndo_fdb_dump</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct napi_struct *) ndo_busy_poll</code>
</li>
<li>
<b>Field removed. </b>
<code>netdev_tx_t (*)(struct sk_buff *, struct net_device *, void *) ndo_dfwd_start_xmit</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rtnl_link_stats64 * (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64</code> ➡️ <code>void (*)(struct net_device *, struct rtnl_link_stats64 *) ndo_get_stats64</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, u32, __be16, struct tc_to_netdev *) ndo_setup_tc</code> ➡️ <code>int (*)(struct net_device *, u32, u32, __be16, struct tc_to_netdev *) ndo_setup_tc</code>
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
<code>int (*)(struct net_device *, struct netdev_bpf *) ndo_bpf</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct xdp_buff *) ndo_xdp_xmit</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net_device *) ndo_xdp_flush</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, struct netdev_xdp *) ndo_xdp</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, u32, u32, __be16, struct tc_to_netdev *) ndo_setup_tc</code> ➡️ <code>int (*)(struct net_device *, enum tc_setup_type, void *) ndo_setup_tc</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct net_device *) ndo_add_slave</code> ➡️ <code>int (*)(struct net_device *, struct net_device *, struct netlink_ext_ack *) ndo_add_slave</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add</code> ➡️ <code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del</code> ➡️ <code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del</code>
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
<code>int (*)(struct net_device *, u32) ndo_xsk_async_xmit</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *) ndo_xdp_flush</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct xdp_buff *) ndo_xdp_xmit</code> ➡️ <code>int (*)(struct net_device *, int, struct xdp_frame * *, u32) ndo_xdp_xmit</code>
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
<code>int (*)(struct sk_buff *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u32, u32, struct netlink_ext_ack *) ndo_fdb_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>u16 (*)(struct net_device *, struct sk_buff *, void *, select_queue_fallback_t) ndo_select_queue</code> ➡️ <code>u16 (*)(struct net_device *, struct sk_buff *, struct net_device *, select_queue_fallback_t) ndo_select_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct nlmsghdr *, u16) ndo_bridge_setlink</code> ➡️ <code>int (*)(struct net_device *, struct nlmsghdr *, u16, struct netlink_ext_ack *) ndo_bridge_setlink</code>
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
<code>int (*)(struct net_device *, struct netdev_phys_item_id *) ndo_get_port_parent_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port</code>
</li>
<li>
<b>Field type changed. </b>
<code>u16 (*)(struct net_device *, struct sk_buff *, struct net_device *, select_queue_fallback_t) ndo_select_queue</code> ➡️ <code>u16 (*)(struct net_device *, struct sk_buff *, struct net_device *) ndo_select_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16) ndo_fdb_add</code> ➡️ <code>int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, u16, struct netlink_ext_ack *) ndo_fdb_add</code>
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
<code>int (*)(struct net_device *, u32, u32) ndo_xsk_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *) ndo_get_lock_subclass</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, u32) ndo_xsk_async_xmit</code>
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
<code>int (*)(struct net_device *, int, struct ifla_vf_guid *, struct ifla_vf_guid *) ndo_get_vf_guid</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * (*)(struct net_device *, struct sk_buff *, bool) ndo_get_xmit_slave</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ip_tunnel_parm *, int) ndo_tunnel_ctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct net_device *) ndo_tx_timeout</code> ➡️ <code>void (*)(struct net_device *, unsigned int) ndo_tx_timeout</code>
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
<code>struct net_device * (*)(struct net_device *, struct sock *) ndo_sk_get_lower_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * (*)(struct net_device *) ndo_get_peer_dev</code>
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
<code>int (*)(struct net_device_path_ctx *, struct net_device_path *) ndo_fill_forward_path</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_add</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *, struct udp_tunnel_info *) ndo_udp_tunnel_del</code>
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
<code>int (*)(struct net_device *, struct ifreq *, int) ndo_eth_ioctl</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ifreq *, int) ndo_siocbond</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct if_settings *) ndo_siocwandev</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct ifreq *, void *, int) ndo_siocdevprivate</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * (*)(struct net_device *, struct xdp_buff *) ndo_xdp_get_xmit_slave</code>
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
<code>int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, u16, struct netlink_ext_ack *) ndo_fdb_del_bulk</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t (*)(struct net_device *, const struct skb_shared_hwtstamps *, bool) ndo_get_tstamp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, bool) ndo_change_proto_down</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16) ndo_fdb_del</code> ➡️ <code>int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, const unsigned char *, u16, struct netlink_ext_ack *) ndo_fdb_del</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct devlink_port * (*)(struct net_device *) ndo_get_devlink_port</code>
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
<code>int (*)(struct net_device *, struct nlattr * *, u16, struct netlink_ext_ack *) ndo_mdb_add</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct nlattr * *, struct netlink_ext_ack *) ndo_mdb_del</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct sk_buff *, struct netlink_callback *) ndo_mdb_dump</code>
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
<code>int (*)(struct net_device *, struct nlattr * *, struct netlink_ext_ack *) ndo_mdb_del_bulk</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct nlattr * *, u32, u32, struct netlink_ext_ack *) ndo_mdb_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct kernel_hwtstamp_config *) ndo_hwtstamp_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, struct kernel_hwtstamp_config *, struct netlink_ext_ack *) ndo_hwtstamp_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ndmsg *, struct nlattr * *, struct net_device *, u16, struct netlink_ext_ack *) ndo_fdb_del_bulk</code> ➡️ <code>int (*)(struct nlmsghdr *, struct net_device *, struct netlink_ext_ack *) ndo_fdb_del_bulk</code>
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
<code>int (*)(struct net_device *) ndo_fcoe_enable</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *) ndo_fcoe_disable</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_setup</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, u16) ndo_fcoe_ddp_done</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, u16, struct scatterlist *, unsigned int) ndo_fcoe_ddp_target</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, struct netdev_fcoe_hbainfo *) ndo_fcoe_get_hbainfo</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, u64 *, int) ndo_fcoe_get_wwn</code>
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
