# Function: <code>devlinks_xa_find_get</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlinks_xa_find_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593793856,
      "name": "devlinks_xa_find_get",
      "external": false,
      "loc": "net/core/devlink.c:298",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_get_from_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793856,
      "name": "devlinks_xa_find_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
struct devlink * devlinks_xa_find_get(struct net * net, long unsigned int * indexp)
```

```json
{
  "name": "devlinks_xa_find_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595894064,
      "name": "devlinks_xa_find_get",
      "external": true,
      "loc": "net/devlink/core.c:103",
      "file": "net/devlink/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/netlink.c:devlink_nl_instance_iter_dumpit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595894064,
      "name": "devlinks_xa_find_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct devlink * devlinks_xa_find_get(struct net * net, long unsigned int * indexp)
```

```json
{
  "name": "devlinks_xa_find_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596675440,
      "name": "devlinks_xa_find_get",
      "external": true,
      "loc": "net/devlink/core.c:326",
      "file": "net/devlink/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596675440,
      "name": "devlinks_xa_find_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct devlink * devlinks_xa_find_get(struct net * net, long unsigned int * indexp)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
