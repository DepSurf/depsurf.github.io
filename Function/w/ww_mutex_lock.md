# Function: <code>ww_mutex_lock</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588313424,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1190",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313424,
      "name": "ww_mutex_lock.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588317296,
      "name": "ww_mutex_lock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588878912,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1190",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878912,
      "name": "ww_mutex_lock.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588882704,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589257840,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1214",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257840,
      "name": "ww_mutex_lock.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071589259600,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589500128,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1392",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589500128,
      "name": "ww_mutex_lock.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071589502128,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962624,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1402",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962624,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590190288,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590190288,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591206656,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591206656,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591701840,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1431",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:destroy_regulator",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591701840,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591646128,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1429",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591646128,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592819632,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1041",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592819632,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594721904,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1097",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594721904,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596472192,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1097",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_mmap",
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596472192,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597016304,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1097",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_mmap",
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597016304,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597945648,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1102",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked",
        "drivers/dma-buf/dma-buf.c:dma_buf_detach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach",
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/gpu/drm/drm_gem.c:drm_gem_vunmap_unlocked",
        "drivers/gpu/drm/drm_gem.c:drm_gem_vmap_unlocked",
        "drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_close",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_open",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_unpin",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597945648,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503935208,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503935208,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236544732,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236544732,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297788400,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297788400,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279803564,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279803564,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589792576,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589792576,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515056,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515056,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590235984,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590235984,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590288000,
      "name": "ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1428",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590288000,
      "name": "ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```
</details>
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
