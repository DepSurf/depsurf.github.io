# Function: <code>sysvipc_find_ipc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140336,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:746",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_next",
        "ipc/util.c:sysvipc_proc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140336,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356384,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:741",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356384,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582447760,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:741",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447760,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582526912,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:687",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526912,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582674288,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:753",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674288,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582867328,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:764",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867328,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582975552,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:725",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975552,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583156576,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156576,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583262640,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262640,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589568,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589568,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583709888,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583709888,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734464,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734464,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095824,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:788",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095824,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690880,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:788",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690880,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585382142,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:800",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
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
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585612718,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:800",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
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
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585859438,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:800",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494993144,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494993144,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228405868,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228405868,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288871664,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288871664,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274286158,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274286158,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583231376,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231376,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583168528,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583168528,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583215408,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215408,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
```

```json
{
  "name": "sysvipc_find_ipc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583309376,
      "name": "sysvipc_find_ipc",
      "external": false,
      "loc": "ipc/util.c:754",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309376,
      "name": "sysvipc_find_ipc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct kern_ipc_perm * sysvipc_find_ipc(struct ipc_ids * ids, loff_t pos, loff_t * new_pos)
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
