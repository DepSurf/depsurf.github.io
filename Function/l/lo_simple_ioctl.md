# Function: <code>lo_simple_ioctl</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585979695,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1548",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586221070,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1599",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586369262,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1697",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143216,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    },
    {
      "addr": 18446744071587146960,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1688",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587227808,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071591492249,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1705",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116480,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071591435312,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1842",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688032,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
    },
    {
      "addr": 18446744071592499489,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1506",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589035680,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    },
    {
      "addr": 18446744071594369821,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1506",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590564336,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    },
    {
      "addr": 18446744071596251994,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1506",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892800,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    },
    {
      "addr": 18446744071596780536,
      "name": "lo_simple_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1500",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236736,
      "name": "lo_simple_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    },
    {
      "addr": 18446744071597689470,
      "name": "lo_simple_ioctl.cold",
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499218424,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231743860,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292421864,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276502860,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586131150,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585975758,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586317230,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
  "name": "lo_simple_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586428782,
      "name": "lo_simple_ioctl",
      "external": false,
      "loc": "drivers/block/loop.c:1619",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl"
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
int lo_simple_ioctl(struct loop_device * lo, unsigned int cmd, long unsigned int arg)
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
