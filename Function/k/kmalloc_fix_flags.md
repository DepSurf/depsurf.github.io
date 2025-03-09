# Function: <code>kmalloc_fix_flags</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591326481,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:811",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmalloc_order",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591326481,
      "name": "kmalloc_fix_flags",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591268823,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:897",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmalloc_order",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591268823,
      "name": "kmalloc_fix_flags",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592195139,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:931",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmalloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592195139,
      "name": "kmalloc_fix_flags",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593971673,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:919",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmalloc_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593971673,
      "name": "kmalloc_fix_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582651326,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:1085",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmalloc_large_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656320,
      "name": "kmalloc_fix_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582860858,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:1098",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmalloc_large_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866432,
      "name": "kmalloc_fix_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
gfp_t kmalloc_fix_flags(gfp_t flags)
```

```json
{
  "name": "kmalloc_fix_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583037648,
      "name": "kmalloc_fix_flags",
      "external": true,
      "loc": "mm/slab_common.c:975",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_large_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037648,
      "name": "kmalloc_fix_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags)
```
</details>
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
