# Function: <code>fsnotify_conn_mask</code>

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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967184,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:123",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967184,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102884,
      "name": "fsnotify_conn_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582100816,
      "name": "fsnotify_conn_mask",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177600,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177600,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415408,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415408,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469520,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469520,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496592,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496592,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811392,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811392,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365824,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365824,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583949776,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949776,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173056,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173056,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387040,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387040,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493735672,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493735672,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227260012,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227260012,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287344832,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287344832,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273344414,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273344414,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146336,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146336,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083776,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083776,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136816,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136816,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
```

```json
{
  "name": "fsnotify_conn_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209840,
      "name": "fsnotify_conn_mask",
      "external": true,
      "loc": "fs/notify/mark.c:111",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209840,
      "name": "fsnotify_conn_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
__u32 fsnotify_conn_mask(struct fsnotify_mark_connector * conn)
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
