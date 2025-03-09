# Function: <code>init_cdrom_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585127008,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1580",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127008,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585521701,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1580",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520112,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585709589,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1580",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585708000,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794224,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1578",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794224,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586232992,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1578",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586232992,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586492128,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1575",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586492128,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586640128,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1575",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586640128,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586893664,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1576",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893664,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587091008,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091008,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587953299,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1586",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_manufact",
        "drivers/cdrom/cdrom.c:dvd_read_bca",
        "drivers/cdrom/cdrom.c:dvd_read_disckey",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937392,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588014099,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1569",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_manufact",
        "drivers/cdrom/cdrom.c:dvd_read_bca",
        "drivers/cdrom/cdrom.c:dvd_read_disckey",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997872,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587894019,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1569",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879936,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588502424,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1569",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483760,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589908312,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1570",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_manufact",
        "drivers/cdrom/cdrom.c:dvd_read_bca",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589888592,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591484600,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1570",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_manufact",
        "drivers/cdrom/cdrom.c:dvd_read_bca",
        "drivers/cdrom/cdrom.c:dvd_read_disckey",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591465872,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591887024,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1553",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_manufact",
        "drivers/cdrom/cdrom.c:dvd_read_bca",
        "drivers/cdrom/cdrom.c:dvd_read_disckey",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591887024,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592626528,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1553",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_read_manufact",
        "drivers/cdrom/cdrom.c:dvd_read_bca",
        "drivers/cdrom/cdrom.c:dvd_read_disckey",
        "drivers/cdrom/cdrom.c:dvd_read_physical",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_read_mech_status",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write",
        "drivers/cdrom/cdrom.c:cdrom_open_write",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592626528,
      "name": "init_cdrom_command",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500160024,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500160024,
      "name": "init_cdrom_command",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232637464,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232637464,
      "name": "init_cdrom_command",
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293435920,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293435920,
      "name": "init_cdrom_command",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277092638,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277091052,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586797088,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797088,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738928,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738928,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587045568,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045568,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void init_cdrom_command(struct packet_command * cgc, void * buf, int len, int type)
```

```json
{
  "name": "init_cdrom_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587152736,
      "name": "init_cdrom_command",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1583",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:dvd_do_auth",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_load_unload",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_release",
        "drivers/cdrom/cdrom.c:cdrom_open",
        "drivers/cdrom/cdrom.c:cdrom_ram_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_get_random_writable",
        "drivers/cdrom/cdrom.c:cdrom_get_media_event",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_mrw_exit",
        "drivers/cdrom/cdrom.c:cdrom_is_mrw",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_get_disc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587152736,
      "name": "init_cdrom_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
