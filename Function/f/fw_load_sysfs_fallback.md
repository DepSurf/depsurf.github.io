# Function: <code>fw_load_sysfs_fallback</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585774364,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:547",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585907647,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:542",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586146852,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586295319,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, u32 opt_flags, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:498",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064272,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071587066013,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:497",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587149184,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071591490142,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036480,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071591433143,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587603792,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    },
    {
      "addr": 18446744071592493928,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:70",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940384,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071594364004,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:70",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590454912,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071596247912,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:70",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590775152,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071596776223,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, long int timeout)
```

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:74",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591117744,
      "name": "fw_load_sysfs_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071597685239,
      "name": "fw_load_sysfs_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499128024,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231675728,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292317520,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276442474,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586058567,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585904519,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586244631,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_load_sysfs_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586354231,
      "name": "fw_load_sysfs_fallback",
      "external": false,
      "loc": "drivers/base/firmware_loader/fallback.c:495",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs * fw_sysfs, u32 opt_flags, long int timeout)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 opt_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>fw_sysfs, opt_flags, timeout</code> ➡️ <code>fw_sysfs, timeout</code>
</li>
</ul>
</details>
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
