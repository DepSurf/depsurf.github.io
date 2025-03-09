# Function: <code>devl_lock</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void devl_lock(struct devlink * devlink)
```

```json
{
  "name": "devl_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591897936,
      "name": "devl_lock",
      "external": true,
      "loc": "net/core/devlink.c:262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591897936,
      "name": "devl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void devl_lock(struct devlink * devlink)
```

```json
{
  "name": "devl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593806236,
      "name": "devl_lock",
      "external": true,
      "loc": "net/core/devlink.c:279",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_trap_groups_unregister",
        "net/core/devlink.c:devlink_trap_groups_register",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_register",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_port_region_create",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resources_unregister",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_sb_unregister",
        "net/core/devlink.c:devlink_sb_register",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_nl_cmd_info_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit",
        "net/core/devlink.c:devlink_nl_pre_doit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593702800,
      "name": "devl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void devl_lock(struct devlink * devlink)
```

```json
{
  "name": "devl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595894303,
      "name": "devl_lock",
      "external": true,
      "loc": "net/devlink/core.c:52",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/core.c:devlink_unregister",
        "net/devlink/core.c:devlink_register"
      ],
      "caller_func": [
        "net/devlink/leftover.c:devlink_trap_groups_unregister",
        "net/devlink/leftover.c:devlink_trap_groups_register",
        "net/devlink/leftover.c:devlink_traps_unregister",
        "net/devlink/leftover.c:devlink_traps_register",
        "net/devlink/leftover.c:devlink_region_destroy",
        "net/devlink/leftover.c:devlink_port_region_create",
        "net/devlink/leftover.c:devlink_region_create",
        "net/devlink/leftover.c:devlink_params_unregister",
        "net/devlink/leftover.c:devlink_params_register",
        "net/devlink/leftover.c:devlink_resource_occ_get_unregister",
        "net/devlink/leftover.c:devlink_resource_occ_get_register",
        "net/devlink/leftover.c:devlink_resources_unregister",
        "net/devlink/leftover.c:devlink_resource_register",
        "net/devlink/leftover.c:devlink_sb_unregister",
        "net/devlink/leftover.c:devlink_sb_register",
        "net/devlink/leftover.c:devlink_port_unregister",
        "net/devlink/leftover.c:devlink_port_register_with_ops",
        "net/devlink/netlink.c:devlink_nl_instance_iter_dumpit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_compat_running_version",
        "net/devlink/health.c:devlink_health_report",
        "net/devlink/health.c:devlink_health_reporter_destroy",
        "net/devlink/health.c:devlink_health_reporter_create",
        "net/devlink/health.c:devlink_port_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595892080,
      "name": "devl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void devl_lock(struct devlink * devlink)
```

```json
{
  "name": "devl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596675728,
      "name": "devl_lock",
      "external": true,
      "loc": "net/devlink/core.c:274",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/core.c:devlink_unregister",
        "net/devlink/core.c:devlink_register"
      ],
      "caller_func": [
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_compat_running_version",
        "net/devlink/port.c:devlink_port_unregister",
        "net/devlink/port.c:devlink_port_register_with_ops",
        "net/devlink/sb.c:devlink_sb_unregister",
        "net/devlink/sb.c:devlink_sb_register",
        "net/devlink/resource.c:devlink_resource_occ_get_unregister",
        "net/devlink/resource.c:devlink_resource_occ_get_register",
        "net/devlink/resource.c:devlink_resources_unregister",
        "net/devlink/resource.c:devlink_resource_register",
        "net/devlink/param.c:devlink_params_unregister",
        "net/devlink/param.c:devlink_params_register",
        "net/devlink/region.c:devlink_region_destroy",
        "net/devlink/region.c:devlink_port_region_create",
        "net/devlink/region.c:devlink_region_create",
        "net/devlink/health.c:devlink_health_report",
        "net/devlink/health.c:devlink_health_report",
        "net/devlink/health.c:devlink_health_reporter_destroy",
        "net/devlink/health.c:devlink_health_reporter_create",
        "net/devlink/health.c:devlink_port_health_reporter_create",
        "net/devlink/trap.c:devlink_trap_groups_unregister",
        "net/devlink/trap.c:devlink_trap_groups_register",
        "net/devlink/trap.c:devlink_traps_unregister",
        "net/devlink/trap.c:devlink_traps_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596664752,
      "name": "devl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void devl_lock(struct devlink * devlink)
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
