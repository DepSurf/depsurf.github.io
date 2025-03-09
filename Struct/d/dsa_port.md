# Struct: <code>dsa_port</code>

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
struct dsa_port {
    struct net_device * netdev;
    struct device_node * dn;
    unsigned int ageing_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * netdev;
    struct device_node * dn;
    unsigned int ageing_time;
    u8 stp_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    struct net_device * netdev;
    struct device_node * dn;
    unsigned int ageing_time;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct ethtool_ops ethtool_ops;
    const struct ethtool_ops * orig_ethtool_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    const struct dsa_port * cpu_dp;
    struct device_node * dn;
    unsigned int ageing_time;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    const struct ethtool_ops * orig_ethtool_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    const struct dsa_port * cpu_dp;
    struct device_node * dn;
    unsigned int ageing_time;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    const struct ethtool_ops * orig_ethtool_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    const struct dsa_port * cpu_dp;
    struct device_node * dn;
    unsigned int ageing_time;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    const struct ethtool_ops * orig_ethtool_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct list_head list;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
    bool setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    bool devlink_port_setup;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct list_head list;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct dsa_netdevice_ops * netdev_ops;
    bool setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    u8[6] mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    bool devlink_port_setup;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct net_device * lag_dev;
    bool lag_tx_enabled;
    struct net_device * hsr_dev;
    struct list_head list;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct dsa_netdevice_ops * netdev_ops;
    bool setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    u8[6] mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    bool learning;
    u8 stp_state;
    struct net_device * bridge_dev;
    int bridge_num;
    struct devlink_port devlink_port;
    bool devlink_port_setup;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct net_device * lag_dev;
    bool lag_tx_enabled;
    struct net_device * hsr_dev;
    struct list_head list;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct dsa_netdevice_ops * netdev_ops;
    struct list_head fdbs;
    struct list_head mdbs;
    bool setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    struct dsa_switch * ds;
    unsigned int index;
    enum (anon) type;
    const char * name;
    struct dsa_port * cpu_dp;
    u8[6] mac;
    u8 stp_state;
    u8 vlan_filtering;
    u8 learning;
    u8 lag_tx_enabled;
    u8 devlink_port_setup;
    u8 master_admin_up;
    u8 master_oper_up;
    u8 setup;
    struct device_node * dn;
    unsigned int ageing_time;
    struct dsa_bridge * bridge;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct dsa_lag * lag;
    struct net_device * hsr_dev;
    struct list_head list;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct dsa_netdevice_ops * netdev_ops;
    struct mutex addr_lists_lock;
    struct list_head fdbs;
    struct list_head mdbs;
    struct mutex vlans_lock;
    struct list_head vlans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    struct dsa_switch * ds;
    unsigned int index;
    enum (anon) type;
    const char * name;
    struct dsa_port * cpu_dp;
    u8[6] mac;
    u8 stp_state;
    u8 vlan_filtering;
    u8 learning;
    u8 lag_tx_enabled;
    u8 master_admin_up;
    u8 master_oper_up;
    u8 cpu_port_in_lag;
    u8 setup;
    struct device_node * dn;
    unsigned int ageing_time;
    struct dsa_bridge * bridge;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct dsa_lag * lag;
    struct net_device * hsr_dev;
    struct list_head list;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct dsa_netdevice_ops * netdev_ops;
    struct mutex addr_lists_lock;
    struct list_head fdbs;
    struct list_head mdbs;
    struct mutex vlans_lock;
    struct list_head vlans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    struct dsa_switch * ds;
    unsigned int index;
    enum (anon) type;
    const char * name;
    struct dsa_port * cpu_dp;
    u8[6] mac;
    u8 stp_state;
    u8 vlan_filtering;
    u8 learning;
    u8 lag_tx_enabled;
    u8 master_admin_up;
    u8 master_oper_up;
    u8 cpu_port_in_lag;
    u8 setup;
    struct device_node * dn;
    unsigned int ageing_time;
    struct dsa_bridge * bridge;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct dsa_lag * lag;
    struct net_device * hsr_dev;
    struct list_head list;
    const struct ethtool_ops * orig_ethtool_ops;
    struct mutex addr_lists_lock;
    struct list_head fdbs;
    struct list_head mdbs;
    struct mutex vlans_lock;
    struct list_head vlans;
    struct list_head user_vlans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * conduit;
    struct net_device * user;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv;
    struct dsa_switch * ds;
    unsigned int index;
    enum (anon) type;
    const char * name;
    struct dsa_port * cpu_dp;
    u8[6] mac;
    u8 stp_state;
    u8 vlan_filtering;
    u8 learning;
    u8 lag_tx_enabled;
    u8 conduit_admin_up;
    u8 conduit_oper_up;
    u8 cpu_port_in_lag;
    u8 setup;
    struct device_node * dn;
    unsigned int ageing_time;
    struct dsa_bridge * bridge;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct dsa_lag * lag;
    struct net_device * hsr_dev;
    struct list_head list;
    const struct ethtool_ops * orig_ethtool_ops;
    struct mutex addr_lists_lock;
    struct list_head fdbs;
    struct list_head mdbs;
    struct mutex vlans_lock;
    struct list_head vlans;
    struct list_head user_vlans;
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
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
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
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dsa_port {
    struct net_device * master;
    struct net_device * slave;
    const struct dsa_device_ops * tag_ops;
    struct dsa_switch_tree * dst;
    struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv;
    bool (*)(const struct sk_buff *, struct net_device *) filter;
    enum (anon) type;
    struct dsa_switch * ds;
    unsigned int index;
    const char * name;
    struct dsa_port * cpu_dp;
    const char * mac;
    struct device_node * dn;
    unsigned int ageing_time;
    bool vlan_filtering;
    u8 stp_state;
    struct net_device * bridge_dev;
    struct devlink_port devlink_port;
    struct phylink * pl;
    struct phylink_config pl_config;
    struct work_struct xmit_work;
    struct sk_buff_head xmit_queue;
    void * priv;
    const struct ethtool_ops * orig_ethtool_ops;
    const struct net_device_ops * orig_ndo_ops;
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
struct dsa_port {
    struct net_device * netdev;
    struct device_node * dn;
    unsigned int ageing_time;
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
<code>u8 stp_state</code>
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
<code>struct dsa_switch * ds</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int index</code>
</li>
<li>
<b>Field added. </b>
<code>const char * name</code>
</li>
<li>
<b>Field added. </b>
<code>struct dsa_port * cpu_dp</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * bridge_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct devlink_port devlink_port</code>
</li>
<li>
<b>Field added. </b>
<code>struct ethtool_ops ethtool_ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct ethtool_ops * orig_ethtool_ops</code>
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
<code>struct net_device * master</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * slave</code>
</li>
<li>
<b>Field added. </b>
<code>const struct dsa_device_ops * tag_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct dsa_switch_tree * dst</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv</code>
</li>
<li>
<b>Field added. </b>
<code>enum (anon) type</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * netdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ethtool_ops ethtool_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dsa_port * cpu_dp</code> ➡️ <code>const struct dsa_port * cpu_dp</code>
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
<code>struct phylink * pl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(const struct sk_buff *, struct net_device *) filter</code>
</li>
<li>
<b>Field added. </b>
<code>const char * mac</code>
</li>
<li>
<b>Field added. </b>
<code>bool vlan_filtering</code>
</li>
<li>
<b>Field added. </b>
<code>struct phylink_config pl_config</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct xmit_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff_head xmit_queue</code>
</li>
<li>
<b>Field added. </b>
<code>void * priv</code>
</li>
<li>
<b>Field added. </b>
<code>const struct net_device_ops * orig_ndo_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct dsa_port * cpu_dp</code> ➡️ <code>struct dsa_port * cpu_dp</code>
</li>
</ul>
</details>
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
<code>struct list_head list</code>
</li>
<li>
<b>Field added. </b>
<code>bool setup</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct xmit_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sk_buff_head xmit_queue</code>
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
<code>bool devlink_port_setup</code>
</li>
<li>
<b>Field added. </b>
<code>const struct dsa_netdevice_ops * netdev_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct net_device_ops * orig_ndo_ops</code>
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
<code>struct net_device * lag_dev</code>
</li>
<li>
<b>Field added. </b>
<code>bool lag_tx_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * hsr_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>const char * mac</code> ➡️ <code>u8[6] mac</code>
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
<code>bool learning</code>
</li>
<li>
<b>Field added. </b>
<code>int bridge_num</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head fdbs</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mdbs</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(const struct sk_buff *, struct net_device *) filter</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff * (*)(struct sk_buff *, struct net_device *, struct packet_type *) rcv</code> ➡️ <code>struct sk_buff * (*)(struct sk_buff *, struct net_device *) rcv</code>
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
<code>u8 master_admin_up</code>
</li>
<li>
<b>Field added. </b>
<code>u8 master_oper_up</code>
</li>
<li>
<b>Field added. </b>
<code>struct dsa_bridge * bridge</code>
</li>
<li>
<b>Field added. </b>
<code>struct dsa_lag * lag</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex addr_lists_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex vlans_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head vlans</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * bridge_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int bridge_num</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * lag_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>void * priv</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool vlan_filtering</code> ➡️ <code>u8 vlan_filtering</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool learning</code> ➡️ <code>u8 learning</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool devlink_port_setup</code> ➡️ <code>u8 devlink_port_setup</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool lag_tx_enabled</code> ➡️ <code>u8 lag_tx_enabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool setup</code> ➡️ <code>u8 setup</code>
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
<code>u8 cpu_port_in_lag</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 devlink_port_setup</code>
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
<code>struct list_head user_vlans</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct dsa_netdevice_ops * netdev_ops</code>
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
<code>struct net_device * conduit</code>
</li>
<li>
<b>Field added. </b>
<code>struct net_device * user</code>
</li>
<li>
<b>Field added. </b>
<code>u8 conduit_admin_up</code>
</li>
<li>
<b>Field added. </b>
<code>u8 conduit_oper_up</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * master</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * slave</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 master_admin_up</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 master_oper_up</code>
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
