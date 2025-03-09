# Function: <code>rio_mport_read_config_32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412528,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:141",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412528,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732272,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:141",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732272,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871808,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:141",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871808,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920720,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:141",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920720,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183952,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:118",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183952,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404080,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:118",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404080,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584499376,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:118",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499376,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696896,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696896,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584832704,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832704,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528144,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_chk_dev_route",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528144,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664016,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_chk_dev_route",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664016,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585544832,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585544832,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586015584,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015584,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587234224,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234224,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588468208,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468208,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747392,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747392,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589050608,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:116",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589050608,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497226288,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497226288,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230413036,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230413036,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291173104,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291173104,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275765886,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275765886,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784176,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784176,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714960,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714960,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785600,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785600,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int rio_mport_read_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 * value)
```

```json
{
  "name": "rio_mport_read_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890448,
      "name": "rio_mport_read_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:114",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_mport_get_feature",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio.c:rio_mport_get_physefb",
        "drivers/rapidio/rio-sysfs.c:rio_read_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890448,
      "name": "rio_mport_read_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
