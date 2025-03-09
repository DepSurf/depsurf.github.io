# Function: <code>devl_assert_locked</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devl_assert_locked(struct devlink * devlink)
```

```json
{
  "name": "devl_assert_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591896160,
      "name": "devl_assert_locked",
      "external": true,
      "loc": "net/core/devlink.c:247",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591896160,
      "name": "devl_assert_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void devl_assert_locked(struct devlink * devlink)
```

```json
{
  "name": "devl_assert_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593698992,
      "name": "devl_assert_locked",
      "external": true,
      "loc": "net/core/devlink.c:264",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593698992,
      "name": "devl_assert_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void devl_assert_locked(struct devlink * devlink)
```

```json
{
  "name": "devl_assert_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595892048,
      "name": "devl_assert_locked",
      "external": true,
      "loc": "net/devlink/core.c:37",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devl_trap_policers_unregister",
        "net/devlink/leftover.c:devl_trap_policers_register",
        "net/devlink/leftover.c:devlink_trap_groups_unregister",
        "net/devlink/leftover.c:devl_trap_groups_register",
        "net/devlink/leftover.c:devl_traps_unregister",
        "net/devlink/leftover.c:devlink_traps_register",
        "net/devlink/leftover.c:devl_region_destroy",
        "net/devlink/leftover.c:devl_region_create",
        "net/devlink/leftover.c:devl_param_driverinit_value_set",
        "net/devlink/leftover.c:devl_rate_nodes_destroy",
        "net/devlink/leftover.c:devl_rate_leaf_destroy",
        "net/devlink/leftover.c:devl_rate_leaf_create",
        "net/devlink/leftover.c:devl_port_register_with_ops",
        "net/devlink/netlink.c:devlink_nl_instance_iter_dumpit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_compat_running_version",
        "net/devlink/health.c:devlink_health_reporter_destroy",
        "net/devlink/health.c:devl_health_reporter_create",
        "net/devlink/health.c:devl_port_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595892048,
      "name": "devl_assert_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void devl_assert_locked(struct devlink * devlink)
```

```json
{
  "name": "devl_assert_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596662416,
      "name": "devl_assert_locked",
      "external": true,
      "loc": "net/devlink/core.c:259",
      "file": "net/devlink/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/netlink.c:devlink_get_from_attrs_lock",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_compat_running_version",
        "net/devlink/port.c:devl_port_register_with_ops",
        "net/devlink/param.c:devl_param_driverinit_value_set",
        "net/devlink/region.c:devl_region_destroy",
        "net/devlink/region.c:devl_region_create",
        "net/devlink/health.c:devlink_health_reporter_destroy",
        "net/devlink/health.c:devl_health_reporter_create",
        "net/devlink/health.c:devl_port_health_reporter_create",
        "net/devlink/trap.c:devl_trap_policers_unregister",
        "net/devlink/trap.c:devl_trap_policers_register",
        "net/devlink/trap.c:devlink_trap_groups_unregister",
        "net/devlink/trap.c:devl_trap_groups_register",
        "net/devlink/trap.c:devl_traps_unregister",
        "net/devlink/trap.c:devlink_traps_register",
        "net/devlink/rate.c:devl_rate_nodes_destroy",
        "net/devlink/rate.c:devl_rate_leaf_destroy",
        "net/devlink/rate.c:devl_rate_leaf_create",
        "net/devlink/rate.c:devlink_rate_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596662416,
      "name": "devl_assert_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void devl_assert_locked(struct devlink * devlink)
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
