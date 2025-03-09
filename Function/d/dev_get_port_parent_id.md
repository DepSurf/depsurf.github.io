# Function: <code>dev_get_port_parent_id</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259072,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:7902",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259072,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464192,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464192,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589329968,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8614",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589329968,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589329296,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8901",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589329296,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224816,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:9160",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224816,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589947040,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:9150",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589947040,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591482672,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8911",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591482672,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593251168,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8898",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593251168,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593712016,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8906",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593712016,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594491104,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:9024",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594491104,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501988360,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501988360,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234745904,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234745904,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295423856,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295423856,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278287372,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278287372,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588070976,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070976,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587784400,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587784400,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588402752,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402752,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```

```json
{
  "name": "dev_get_port_parent_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588539216,
      "name": "dev_get_port_parent_id",
      "external": true,
      "loc": "net/core/dev.c:8201",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:netdev_port_same_parent_id",
        "net/core/dev.c:dev_get_port_parent_id",
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588539216,
      "name": "dev_get_port_parent_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int dev_get_port_parent_id(struct net_device * dev, struct netdev_phys_item_id * ppid, bool recurse)
```
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
