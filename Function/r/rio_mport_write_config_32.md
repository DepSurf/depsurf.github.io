# Function: <code>rio_mport_write_config_32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583413360,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:144",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413360,
      "name": "rio_mport_write_config_32",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583733136,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:144",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733136,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583872672,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:144",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872672,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583921584,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:144",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921584,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184224,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:121",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184224,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404352,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:121",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404352,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584499648,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:121",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499648,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584697168,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697168,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584832976,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832976,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528432,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528432,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664304,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664304,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545104,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545104,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586015856,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015856,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587234576,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234576,
      "name": "rio_mport_write_config_32",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588468608,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468608,
      "name": "rio_mport_write_config_32",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747792,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747792,
      "name": "rio_mport_write_config_32",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589051008,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:119",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051008,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497226696,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497226696,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230413376,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230413376,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291173552,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291173552,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275766166,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275766166,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784448,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784448,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715232,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715232,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785872,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785872,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int rio_mport_write_config_32(struct rio_mport * mport, u16 destid, u8 hopcount, u32 offset, u32 value)
```

```json
{
  "name": "rio_mport_write_config_32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890720,
      "name": "rio_mport_write_config_32",
      "external": true,
      "loc": "drivers/rapidio/rio-access.c:117",
      "file": "drivers/rapidio/rio-access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_unlock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_inb_pwrite_handler",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_set_port_lockout",
        "drivers/rapidio/rio-sysfs.c:rio_write_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890720,
      "name": "rio_mport_write_config_32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
