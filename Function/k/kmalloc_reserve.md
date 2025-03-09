# Function: <code>kmalloc_reserve</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * kmalloc_reserve(size_t size, gfp_t flags, int node, bool * pfmemalloc)
```

```json
{
  "name": "kmalloc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589166647,
      "name": "kmalloc_reserve",
      "external": false,
      "loc": "net/core/skbuff.c:344",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589134224,
      "name": "kmalloc_reserve",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * kmalloc_reserve(size_t size, gfp_t flags, int node, bool * pfmemalloc)
```

```json
{
  "name": "kmalloc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589887111,
      "name": "kmalloc_reserve",
      "external": false,
      "loc": "net/core/skbuff.c:346",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589853632,
      "name": "kmalloc_reserve",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * kmalloc_reserve(size_t size, gfp_t flags, int node, bool * pfmemalloc)
```

```json
{
  "name": "kmalloc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591416001,
      "name": "kmalloc_reserve",
      "external": false,
      "loc": "net/core/skbuff.c:344",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378544,
      "name": "kmalloc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void * kmalloc_reserve(size_t size, gfp_t flags, int node, bool * pfmemalloc)
```

```json
{
  "name": "kmalloc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593181261,
      "name": "kmalloc_reserve",
      "external": false,
      "loc": "net/core/skbuff.c:482",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ],
      "caller_func": [
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139104,
      "name": "kmalloc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void * kmalloc_reserve(unsigned int * size, gfp_t flags, int node, bool * pfmemalloc)
```

```json
{
  "name": "kmalloc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593591632,
      "name": "kmalloc_reserve",
      "external": false,
      "loc": "net/core/skbuff.c:549",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593591632,
      "name": "kmalloc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void * kmalloc_reserve(unsigned int * size, gfp_t flags, int node, bool * pfmemalloc)
```

```json
{
  "name": "kmalloc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594364512,
      "name": "kmalloc_reserve",
      "external": false,
      "loc": "net/core/skbuff.c:550",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594364512,
      "name": "kmalloc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void * kmalloc_reserve(size_t size, gfp_t flags, int node, bool * pfmemalloc)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>unsigned int * size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
