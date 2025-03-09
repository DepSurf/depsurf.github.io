# Function: <code>ncsi_reset_dev</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589335616,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1804",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589335616,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589790592,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1800",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589790592,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590013872,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590013872,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591045680,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1794",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591045680,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591109296,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1791",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109296,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591039696,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1797",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591039696,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591882048,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1865",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591882048,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593601248,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1866",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593601248,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595529216,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1866",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595529216,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596037760,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1866",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037760,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596902432,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1857",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596902432,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503761744,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503761744,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236386160,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236386160,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297602624,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297602624,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279677238,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279677238,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589617472,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589617472,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589342000,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589342000,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590059504,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590059504,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int ncsi_reset_dev(struct ncsi_dev * nd)
```

```json
{
  "name": "ncsi_reset_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109600,
      "name": "ncsi_reset_dev",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:1728",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109600,
      "name": "ncsi_reset_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int ncsi_reset_dev(struct ncsi_dev * nd)
```
</details>
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
