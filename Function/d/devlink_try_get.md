# Function: <code>devlink_try_get</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_try_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590389727,
      "name": "devlink_try_get",
      "external": false,
      "loc": "net/core/devlink.c:118",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_get_from_attrs"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devlink * devlink_try_get(struct devlink * devlink)
```

```json
{
  "name": "devlink_try_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591980080,
      "name": "devlink_try_get",
      "external": true,
      "loc": "net/core/devlink.c:240",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_get_from_attrs",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_drvinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591980080,
      "name": "devlink_try_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct devlink * devlink_try_get(struct devlink * devlink)
```

```json
{
  "name": "devlink_try_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593793744,
      "name": "devlink_try_get",
      "external": true,
      "loc": "net/core/devlink.c:257",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_drvinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793744,
      "name": "devlink_try_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct devlink * devlink_try_get(struct devlink * devlink)
```

```json
{
  "name": "devlink_try_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595893328,
      "name": "devlink_try_get",
      "external": true,
      "loc": "net/devlink/core.c:79",
      "file": "net/devlink/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_drvinfo",
        "net/devlink/core.c:devlinks_xa_find_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595893328,
      "name": "devlink_try_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct devlink * devlink_try_get(struct devlink * devlink)
```

```json
{
  "name": "devlink_try_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596673984,
      "name": "devlink_try_get",
      "external": true,
      "loc": "net/devlink/core.c:301",
      "file": "net/devlink/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_drvinfo",
        "net/devlink/core.c:devlinks_xa_find_get",
        "net/devlink/core.c:devlink_rel_devlink_handle_put",
        "net/devlink/core.c:devlink_rel_nested_in_notify_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596673984,
      "name": "devlink_try_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct devlink * devlink_try_get(struct devlink * devlink)
```
</details>
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
