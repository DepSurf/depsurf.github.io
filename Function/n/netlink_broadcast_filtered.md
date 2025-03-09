# Function: <code>netlink_broadcast_filtered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586494688,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2076",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:nlmsg_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494688,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941120,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1383",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941120,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136368,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1400",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136368,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587267408,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1435",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267408,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587787184,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1448",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587787184,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588128848,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1487",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588128848,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588311344,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1480",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311344,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709360,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1480",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709360,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588933264,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933264,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589826464,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589826464,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861328,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1482",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861328,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589767376,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1492",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767376,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590526672,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590526672,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, netlink_filter_fn filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595140016,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1519",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/regulator/event.c:reg_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "drivers/dpll/dpll_netlink.c:dpll_pin_event_send",
        "drivers/dpll/dpll_netlink.c:dpll_device_event_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/netdev-genl.c:netdev_genl_dev_notify",
        "net/core/page_pool_user.c:netdev_nl_page_pool_event",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ethtool/netlink.c:ethnl_multicast",
        "net/devlink/port.c:devlink_port_notify",
        "net/devlink/region.c:devlink_nl_region_notify",
        "net/devlink/rate.c:devlink_rate_notify",
        "net/devlink/linecard.c:devlink_linecard_notify",
        "net/mptcp/pm_netlink.c:mptcp_nl_mcast_send",
        "net/handshake/netlink.c:handshake_genl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595140016,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
    }
  ]
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
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502526232,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502526232,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235237508,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235237508,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296101008,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296101008,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278697216,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278697216,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1014
    }
  ]
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
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588539648,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588539648,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588251648,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251648,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588871824,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588871824,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```

```json
{
  "name": "netlink_broadcast_filtered",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589013344,
      "name": "netlink_broadcast_filtered",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1481",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589013344,
      "name": "netlink_broadcast_filtered",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
    }
  ]
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, int (*)(struct sock *, struct sk_buff *, void *) filter, void * filter_data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int netlink_broadcast_filtered(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation, netlink_filter_fn filter, void * filter_data)
```
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
