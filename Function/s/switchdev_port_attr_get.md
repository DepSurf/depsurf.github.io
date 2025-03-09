# Function: <code>switchdev_port_attr_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_attr_get",
      "external": false,
      "loc": "include/net/switchdev.h:217",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "switchdev_port_attr_get",
      "external": false,
      "loc": "include/net/switchdev.h:217",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587799584,
      "name": "switchdev_port_attr_get",
      "external": true,
      "loc": "net/switchdev/switchdev.c:184",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_get_dev_by_nhs",
        "net/switchdev/switchdev.c:switchdev_port_br_setflag",
        "net/switchdev/switchdev.c:switchdev_port_bridge_getlink",
        "net/switchdev/switchdev.c:switchdev_port_attr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587799584,
      "name": "switchdev_port_attr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588014320,
      "name": "switchdev_port_attr_get",
      "external": true,
      "loc": "net/switchdev/switchdev.c:183",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_br_setflag",
        "net/switchdev/switchdev.c:switchdev_port_bridge_getlink",
        "net/switchdev/switchdev.c:switchdev_port_attr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588014320,
      "name": "switchdev_port_attr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588172624,
      "name": "switchdev_port_attr_get",
      "external": true,
      "loc": "net/switchdev/switchdev.c:183",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_br_setflag",
        "net/switchdev/switchdev.c:switchdev_port_bridge_getlink",
        "net/switchdev/switchdev.c:switchdev_port_attr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588172624,
      "name": "switchdev_port_attr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588720432,
      "name": "switchdev_port_attr_get",
      "external": true,
      "loc": "net/switchdev/switchdev.c:183",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/ipv4/ipmr.c:vif_add",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_attr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588720432,
      "name": "switchdev_port_attr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589087920,
      "name": "switchdev_port_attr_get",
      "external": true,
      "loc": "net/switchdev/switchdev.c:183",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/ipv4/ipmr.c:vif_add",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_attr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589087920,
      "name": "switchdev_port_attr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```

```json
{
  "name": "switchdev_port_attr_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589314864,
      "name": "switchdev_port_attr_get",
      "external": true,
      "loc": "net/switchdev/switchdev.c:183",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_phys_switch_id_fill",
        "net/ipv4/ipmr.c:vif_add",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_same_parent_id",
        "net/switchdev/switchdev.c:switchdev_port_attr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589314864,
      "name": "switchdev_port_attr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int switchdev_port_attr_get(struct net_device * dev, struct switchdev_attr * attr)
```
</details>
</li>
</ul>
