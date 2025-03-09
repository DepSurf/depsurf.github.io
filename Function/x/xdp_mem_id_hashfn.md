# Function: <code>xdp_mem_id_hashfn</code>

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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996976,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:40",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996976,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588156336,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:43",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156336,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477840,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:__mem_id_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477840,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588683264,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588683264,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589549440,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:36",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589549440,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589558544,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:36",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589558544,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589456496,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:36",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456496,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590193936,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:36",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590193936,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591757264,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:36",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591757264,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593548224,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:36",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593548224,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594019512,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:38",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_unreg_mem_model"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594016928,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594805640,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:38",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_unreg_mem_model"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594803296,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502238192,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502238192,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234982988,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234982988,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295729392,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_allocator_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295729392,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278479716,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_allocator_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278479716,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588290000,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588290000,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002816,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002816,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621824,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:mem_id_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621824,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```

```json
{
  "name": "xdp_mem_id_hashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759792,
      "name": "xdp_mem_id_hashfn",
      "external": false,
      "loc": "net/core/xdp.c:34",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759792,
      "name": "xdp_mem_id_hashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
u32 xdp_mem_id_hashfn(const void * data, u32 len, u32 seed)
```
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
