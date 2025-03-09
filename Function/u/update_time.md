# Function: <code>update_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581103895,
      "name": "update_time",
      "external": false,
      "loc": "fs/inode.c:1587",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269543,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1596",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265936,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int update_time(struct inode * inode, struct timespec * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347654,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1645",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343776,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int update_time(struct inode * inode, struct timespec * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403129,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1645",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399248,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544761,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1658",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540848,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699480,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1652",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696240,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785816,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1660",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782592,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904145,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1673",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900480,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976641,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972816,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582210473,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1771",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208752,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582257961,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1772",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256224,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582283369,
      "name": "update_time",
      "external": false,
      "loc": "fs/inode.c:1781",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493482704,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493479728,
      "name": "update_time",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227047388,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227042300,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287044252,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287038128,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273160218,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273156486,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945377,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941552,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581882945,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879136,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936689,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932864,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008129,
      "name": "update_time",
      "external": true,
      "loc": "fs/inode.c:1684",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003984,
      "name": "update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int update_time(struct inode * inode, struct timespec * time, int flags)
```
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * time</code> ➡️ <code>struct timespec64 * time</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int update_time(struct inode * inode, struct timespec64 * time, int flags)
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
