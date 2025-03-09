# Function: <code>cdrom_mode_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585128848,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1994",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585128848,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521888,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1994",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521888,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585709776,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1994",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709776,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585796016,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1992",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796016,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586234848,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1992",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234848,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586493792,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1989",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586493792,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586641792,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1989",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586641792,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586895376,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1990",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895376,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092720,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092720,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587952105,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:2000",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940144,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588012905,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1983",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000624,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587892761,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1983",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587881952,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588501097,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1983",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588484816,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589908054,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1985",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890080,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591486100,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1985",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591466544,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591887696,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1968",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591887696,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592627200,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1968",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592627200,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500162200,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500162200,
      "name": "cdrom_mode_sense",
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232639684,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232639684,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293438720,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293438720,
      "name": "cdrom_mode_sense",
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277092840,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277092840,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798800,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798800,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586740640,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586740640,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587047280,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047280,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int cdrom_mode_sense(struct cdrom_device_info * cdi, struct packet_command * cgc, int page_code, int page_control)
```

```json
{
  "name": "cdrom_mode_sense",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587154448,
      "name": "cdrom_mode_sense",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1997",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:mo_open_write",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc",
        "drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154448,
      "name": "cdrom_mode_sense",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
