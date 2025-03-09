# Function: <code>rproc_check_carveout_da</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:282",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233136,
      "name": "rproc_check_carveout_da.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071588238698,
      "name": "rproc_check_carveout_da.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:286",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105744,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071589113861,
      "name": "rproc_check_carveout_da.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:286",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104624,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591615941,
      "name": "rproc_check_carveout_da.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:289",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993856,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591558968,
      "name": "rproc_check_carveout_da.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:291",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589707936,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071592679578,
      "name": "rproc_check_carveout_da.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:291",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591215168,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071594564977,
      "name": "rproc_check_carveout_da.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592958992,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:290",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592958992,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593409360,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:290",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593409360,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594155072,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:290",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594155072,
      "name": "rproc_check_carveout_da",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501690320,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:282",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501690320,
      "name": "rproc_check_carveout_da.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234212840,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:282",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234212840,
      "name": "rproc_check_carveout_da",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295122160,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:282",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295122160,
      "name": "rproc_check_carveout_da.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:282",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844832,
      "name": "rproc_check_carveout_da.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587850394,
      "name": "rproc_check_carveout_da.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_check_carveout_da",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_check_carveout_da",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:282",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588305472,
      "name": "rproc_check_carveout_da.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071588311034,
      "name": "rproc_check_carveout_da.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int rproc_check_carveout_da(struct rproc * rproc, struct rproc_mem_entry * mem, u32 da, u32 len)
```
</details>
</li>
</ul>
