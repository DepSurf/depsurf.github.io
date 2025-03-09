# Function: <code>xas_start</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589425376,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:173",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425376,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589883248,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:178",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883248,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590109152,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109152,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110800,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110800,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259984,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259984,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143584,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143584,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594176,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071592344613,
      "name": "xas_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750576,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071594206199,
      "name": "xas_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595914416,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071596375165,
      "name": "xas_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:181",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596432192,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071596904688,
      "name": "xas_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:181",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597327552,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071597829781,
      "name": "xas_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503890488,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503890488,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236519068,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236519068,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297756960,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297756960,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279782042,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279782042,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589711408,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711408,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589437184,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437184,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590154784,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154784,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
```

```json
{
  "name": "xas_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590205168,
      "name": "xas_start",
      "external": false,
      "loc": "lib/xarray.c:179",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:xa_get_mark",
        "lib/xarray.c:xas_find_conflict",
        "lib/xarray.c:xas_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205168,
      "name": "xas_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void * xas_start(struct xa_state * xas)
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
