# Function: <code>flow_block_cb_alloc</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588484389,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:168",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588484016,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588689685,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689312,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589555861,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:205",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc"
      ],
      "caller_func": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589555760,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589565031,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:205",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589564896,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589463319,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:205",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463184,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590201687,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:205",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201088,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591767291,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:226",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591767136,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593558747,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:254",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593558576,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594028027,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:254",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594027856,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594814976,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:261",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_indr_block_cb_alloc",
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594814752,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502246492,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502245968,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234990876,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234990432,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295742448,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295740352,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278486362,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278485994,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588296421,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296048,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588009237,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588008864,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588628245,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588627872,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```

```json
{
  "name": "flow_block_cb_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588766661,
      "name": "flow_block_cb_alloc",
      "external": true,
      "loc": "net/core/flow_offload.c:170",
      "file": "net/core/flow_offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:flow_block_cb_setup_simple"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766288,
      "name": "flow_block_cb_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct flow_block_cb * flow_block_cb_alloc(flow_setup_cb_t * cb, void * cb_ident, void * cb_priv, void (*)(void *) release)
```
</details>
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
