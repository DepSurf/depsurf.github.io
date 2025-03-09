# Struct: <code>rtnl_link_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct nlattr * *, struct nlattr * *) slave_validate;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct nlattr * *, struct nlattr * *) slave_validate;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct nlattr * *, struct nlattr * *) slave_validate;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_validate;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    struct net_device * (*)(struct nlattr * *, const char *, unsigned char, unsigned int, unsigned int) alloc;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    struct net_device * (*)(struct nlattr * *, const char *, unsigned char, unsigned int, unsigned int) alloc;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    struct net_device * (*)(struct nlattr * *, const char *, unsigned char, unsigned int, unsigned int) alloc;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    struct net_device * (*)(struct nlattr * *, const char *, unsigned char, unsigned int, unsigned int) alloc;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    struct net_device * (*)(struct nlattr * *, const char *, unsigned char, unsigned int, unsigned int) alloc;
    void (*)(struct net_device *) setup;
    bool netns_refund;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
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
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
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
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtnl_link_ops {
    struct list_head list;
    const char * kind;
    size_t priv_size;
    void (*)(struct net_device *) setup;
    unsigned int maxtype;
    const struct nla_policy * policy;
    int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate;
    int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink;
    int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink;
    void (*)(struct net_device *, struct list_head *) dellink;
    size_t (*)(const struct net_device *) get_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_info;
    size_t (*)(const struct net_device *) get_xstats_size;
    int (*)(struct sk_buff *, const struct net_device *) fill_xstats;
    unsigned int (*)() get_num_tx_queues;
    unsigned int (*)() get_num_rx_queues;
    unsigned int slave_maxtype;
    const struct nla_policy * slave_policy;
    int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink;
    size_t (*)(const struct net_device *, const struct net_device *) get_slave_size;
    int (*)(struct sk_buff *, const struct net_device *, const struct net_device *) fill_slave_info;
    struct net * (*)(const struct net_device *) get_link_net;
    size_t (*)(const struct net_device *, int) get_linkxstats_size;
    int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats;
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
<code>size_t (*)(const struct net_device *, int) get_linkxstats_size</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, const struct net_device *, int *, int) fill_linkxstats</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct nlattr * *, struct nlattr * *) validate</code> ➡️ <code>int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *) newlink</code> ➡️ <code>int (*)(struct net *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) newlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct nlattr * *, struct nlattr * *) changelink</code> ➡️ <code>int (*)(struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) changelink</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct nlattr * *, struct nlattr * *) slave_validate</code> ➡️ <code>int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *) slave_changelink</code> ➡️ <code>int (*)(struct net_device *, struct net_device *, struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_changelink</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct nlattr * *, struct nlattr * *, struct netlink_ext_ack *) slave_validate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int maxtype</code> ➡️ <code>unsigned int maxtype</code>
</li>
<li>
<b>Field type changed. </b>
<code>int slave_maxtype</code> ➡️ <code>unsigned int slave_maxtype</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool netns_refund</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct net_device * (*)(struct nlattr * *, const char *, unsigned char, unsigned int, unsigned int) alloc</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
