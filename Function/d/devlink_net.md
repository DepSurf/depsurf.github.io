# Function: <code>devlink_net</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588590183,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:95",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588822689,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589715017,
      "name": "devlink_net",
      "external": true,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/core/devlink.c:devlink_get_from_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658944,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589754604,
      "name": "devlink_net",
      "external": true,
      "loc": "net/core/devlink.c:102",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_notify",
        "net/core/devlink.c:devlink_get_from_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589684176,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589635564,
      "name": "devlink_net",
      "external": true,
      "loc": "net/core/devlink.c:105",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_notify",
        "net/core/devlink.c:devlink_get_from_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589565344,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590389766,
      "name": "devlink_net",
      "external": true,
      "loc": "net/core/devlink.c:106",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_rate_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_notify",
        "net/core/devlink.c:devlink_get_from_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590310784,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591992068,
      "name": "devlink_net",
      "external": true,
      "loc": "net/core/devlink.c:228",
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
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit",
        "net/core/devlink.c:devlink_linecard_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_rate_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_notify",
        "net/core/devlink.c:devlink_get_from_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591896128,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593780155,
      "name": "devlink_net",
      "external": true,
      "loc": "net/core/devlink.c:234",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_netdevice_event",
        "net/core/devlink.c:devlink_netdevice_event",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_linecard_notify",
        "net/core/devlink.c:devlink_rate_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593698944,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595894104,
      "name": "devlink_net",
      "external": true,
      "loc": "net/devlink/core.c:31",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/core.c:devlinks_xa_find_get"
      ],
      "caller_func": [
        "net/devlink/leftover.c:devlink_port_netdevice_event",
        "net/devlink/leftover.c:devlink_port_netdevice_event",
        "net/devlink/leftover.c:devlink_nl_region_notify",
        "net/devlink/leftover.c:devlink_linecard_notify",
        "net/devlink/leftover.c:devlink_rate_notify",
        "net/devlink/leftover.c:devlink_port_notify",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_reload",
        "net/devlink/dev.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595892000,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct net * devlink_net(const struct devlink * devlink)
```

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596675480,
      "name": "devlink_net",
      "external": true,
      "loc": "net/devlink/core.c:253",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/core.c:devlinks_xa_find_get",
        "net/devlink/core.c:devlink_rel_devlink_handle_put"
      ],
      "caller_func": [
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_reload",
        "net/devlink/port.c:devlink_port_netdevice_event",
        "net/devlink/port.c:devlink_port_netdevice_event",
        "net/devlink/port.c:devlink_port_notify",
        "net/devlink/port.c:devlink_port_notify",
        "net/devlink/region.c:devlink_nl_region_notify",
        "net/devlink/region.c:devlink_nl_region_notify",
        "net/devlink/rate.c:devlink_rate_notify",
        "net/devlink/rate.c:devlink_rate_notify",
        "net/devlink/linecard.c:devlink_linecard_notify",
        "net/devlink/linecard.c:devlink_linecard_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596662368,
      "name": "devlink_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502396136,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235131500,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295939000,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278608412,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588429073,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588141761,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588761249,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_net",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588901777,
      "name": "devlink_net",
      "external": false,
      "loc": "net/core/devlink.c:98",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct net * devlink_net(const struct devlink * devlink)
```
</details>
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
