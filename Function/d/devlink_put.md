# Function: <code>devlink_put</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void devlink_put(struct devlink * devlink)
```

```json
{
  "name": "devlink_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590326176,
      "name": "devlink_put",
      "external": false,
      "loc": "net/core/devlink.c:112",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_nl_post_doit",
        "net/core/devlink.c:devlink_nl_pre_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590326176,
      "name": "devlink_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void devlink_put(struct devlink * devlink)
```

```json
{
  "name": "devlink_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591979344,
      "name": "devlink_put",
      "external": true,
      "loc": "net/core/devlink.c:234",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
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
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_nl_post_doit",
        "net/core/devlink.c:devlink_nl_pre_doit",
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591979344,
      "name": "devlink_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devlink_put(struct devlink * devlink)
```

```json
{
  "name": "devlink_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593793328,
      "name": "devlink_put",
      "external": true,
      "loc": "net/core/devlink.c:247",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
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
        "net/core/devlink.c:devlink_nl_post_doit",
        "net/core/devlink.c:devlink_nl_pre_doit",
        "net/core/devlink.c:devlink_get_from_attrs",
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793328,
      "name": "devlink_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devlink_put(struct devlink * devlink)
```

```json
{
  "name": "devlink_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595893440,
      "name": "devlink_put",
      "external": true,
      "loc": "net/devlink/core.c:97",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlinks_xa_find_get",
        "net/devlink/netlink.c:devlink_nl_instance_iter_dumpit",
        "net/devlink/netlink.c:devlink_nl_instance_iter_dumpit",
        "net/devlink/netlink.c:devlink_nl_post_doit",
        "net/devlink/netlink.c:devlink_nl_pre_doit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595893440,
      "name": "devlink_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devlink_put(struct devlink * devlink)
```

```json
{
  "name": "devlink_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596674096,
      "name": "devlink_put",
      "external": true,
      "loc": "net/devlink/core.c:320",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlinks_xa_find_get",
        "net/devlink/core.c:devlink_rel_devlink_handle_put",
        "net/devlink/core.c:devlink_rel_nested_in_notify_work",
        "net/devlink/core.c:devlink_rel_nested_in_notify_work",
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_nl_post_doit_dev_lock",
        "net/devlink/netlink.c:devlink_nl_post_doit",
        "net/devlink/netlink.c:devlink_nl_pre_doit_port",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596674096,
      "name": "devlink_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void devlink_put(struct devlink * devlink)
```
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
