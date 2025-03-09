# Function: <code>devlink_nl_put_handle</code>

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
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588581776,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:458",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588581776,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588800064,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588800064,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589683408,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:469",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683408,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589713168,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:473",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589713168,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589590864,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:476",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590864,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590339904,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:573",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590339904,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591928096,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:790",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591928096,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593732624,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:930",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_cmd_selftests_run",
        "net/core/devlink.c:devlink_nl_selftests_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_nl_port_handle_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593732624,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595849299,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:142",
      "file": "net/devlink/leftover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_port_handle_fill"
      ],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_region_notify_build",
        "net/devlink/leftover.c:devlink_nl_port_fill"
      ]
    },
    {
      "addr": 18446744071595907357,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:142",
      "file": "net/devlink/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/dev.c:devlink_nl_cmd_selftests_run",
        "net/devlink/dev.c:devlink_nl_selftests_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595914565,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:142",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_nl_health_reporter_fill"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595837456,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596676763,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/netlink.c:devlink_nl_put_nested_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596692064,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/dev.c:devlink_nl_selftests_run_doit",
        "net/devlink/dev.c:devlink_nl_selftests_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596697593,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/port.c:devlink_nl_port_fill",
        "net/devlink/port.c:devlink_nl_port_handle_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596705376,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/sb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596714766,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/dpipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596722113,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596728006,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/param.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596741128,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_notify_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596749941,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_nl_health_reporter_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596755587,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/trap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596771349,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/rate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596775652,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/devlink/devl_internal.h:175",
      "file": "net/devlink/linecard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596705376,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502372256,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502372256,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235108024,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235108024,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295903472,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295903472,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278584438,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278584438,
      "name": "devlink_nl_put_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588406448,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406448,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588119136,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588119136,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588738624,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738624,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_put_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588879152,
      "name": "devlink_nl_put_handle",
      "external": false,
      "loc": "net/core/devlink.c:453",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879152,
      "name": "devlink_nl_put_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int devlink_nl_put_handle(struct sk_buff * msg, struct devlink * devlink)
```
</details>
</li>
</ul>
