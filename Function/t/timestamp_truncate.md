# Function: <code>timestamp_truncate</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976160,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976160,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582209933,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2250",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208112,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582257421,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2251",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255584,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582283016,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2277",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281392,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582601064,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2282",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599440,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583134537,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2363",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132368,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583705321,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2412",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702880,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922729,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2457",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:current_time"
      ],
      "caller_func": [
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920368,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126064,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2460",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_needs_update_time",
        "fs/inode.c:inode_update_timestamps",
        "fs/inode.c:inode_update_timestamps",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126064,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493482144,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493482144,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227043712,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227043712,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287043504,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287043504,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273159754,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273159754,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944896,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944896,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882464,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882464,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936208,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936208,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```

```json
{
  "name": "timestamp_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007648,
      "name": "timestamp_truncate",
      "external": true,
      "loc": "fs/inode.c:2190",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007648,
      "name": "timestamp_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode * inode)
```
</details>
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
