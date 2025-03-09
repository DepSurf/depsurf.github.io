# Function: <code>device_connection_find_match</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, void * (*)(struct device_connection *, int, void *) match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585703904,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:25",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703904,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, void * (*)(struct device_connection *, int, void *) match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585832176,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:25",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585832176,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586067408,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:74",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586067408,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586215440,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215440,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980656,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980656,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588461341,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:444",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588343949,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:447",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589003005,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:447",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590438790,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:447",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592077766,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:453",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592500486,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:464",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593244641,
      "name": "device_connection_find_match",
      "external": false,
      "loc": "include/linux/property.h:504",
      "file": "drivers/usb/roles/class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499023584,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499023584,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231584936,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231584936,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292186784,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292186784,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276390446,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276390446,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975648,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975648,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585824912,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824912,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165456,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165456,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```

```json
{
  "name": "device_connection_find_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274160,
      "name": "device_connection_find_match",
      "external": true,
      "loc": "drivers/base/devcon.c:99",
      "file": "drivers/base/devcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274160,
      "name": "device_connection_find_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, void * (*)(struct device_connection *, int, void *) match)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * (*)(struct device_connection *, int, void *) match</code> ➡️ <code>devcon_match_fn_t match</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void * device_connection_find_match(struct device * dev, const char * con_id, void * data, devcon_match_fn_t match)
```
</details>
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
