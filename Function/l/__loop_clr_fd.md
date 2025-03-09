# Function: <code>__loop_clr_fd</code>

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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585970320,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1086",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970320,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1123",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213520,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
    },
    {
      "addr": 18446744071586225517,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361568,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
    },
    {
      "addr": 18446744071586373738,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1251",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131440,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
    },
    {
      "addr": 18446744071587146809,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1243",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587216512,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
    },
    {
      "addr": 18446744071591492090,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1250",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106096,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071591435150,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1373",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693152,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1386
    },
    {
      "addr": 18446744071592499768,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1136",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589025936,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071594369359,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1136",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590553952,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071596251602,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1136",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590882368,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071596780146,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1132",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591225872,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
    },
    {
      "addr": 18446744071597689059,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499213768,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499213768,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231737100,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231737100,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292412000,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292412000,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
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
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276495208,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276495208,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586123456,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
    },
    {
      "addr": 18446744071586135626,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968080,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1007
    },
    {
      "addr": 18446744071585980234,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586309536,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
    },
    {
      "addr": 18446744071586321706,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __loop_clr_fd(struct loop_device * lo, bool release)
```

```json
{
  "name": "__loop_clr_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__loop_clr_fd",
      "external": false,
      "loc": "drivers/block/loop.c:1143",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421216,
      "name": "__loop_clr_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
    },
    {
      "addr": 18446744071586433271,
      "name": "__loop_clr_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __loop_clr_fd(struct loop_device * lo, bool release)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
