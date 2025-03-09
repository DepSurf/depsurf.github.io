# Function: <code>memcg_slab_free_hook</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581886825,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slab.h:337",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876032,
      "name": "memcg_slab_free_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581917481,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slab.h:335",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910432,
      "name": "memcg_slab_free_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void memcg_slab_free_hook(struct kmem_cache * s_orig, void * * p, int objects)
```

```json
{
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582230578,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slab.h:331",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202160,
      "name": "memcg_slab_free_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    },
    {
      "addr": 18446744071592218625,
      "name": "memcg_slab_free_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void memcg_slab_free_hook(struct kmem_cache * s_orig, void * * p, int objects)
```

```json
{
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582697677,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slab.h:550",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668432,
      "name": "memcg_slab_free_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071593997522,
      "name": "memcg_slab_free_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void memcg_slab_free_hook(struct kmem_cache * s, struct slab * slab, void * * p, int objects)
```

```json
{
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583219817,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slab.h:556",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195152,
      "name": "memcg_slab_free_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071596045321,
      "name": "memcg_slab_free_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void memcg_slab_free_hook(struct kmem_cache * s, struct slab * slab, void * * p, int objects)
```

```json
{
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583438317,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slab.h:548",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412672,
      "name": "memcg_slab_free_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071596567754,
      "name": "memcg_slab_free_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_slab_free_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583405147,
      "name": "memcg_slab_free_hook",
      "external": false,
      "loc": "mm/slub.c:2018",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void memcg_slab_free_hook(struct kmem_cache * s_orig, void * * p, int objects)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kmem_cache * s</code>
</li>
<li>
<b>Param added. </b>
<code>struct slab * slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kmem_cache * s_orig</code>
</li>
<li>
<b>Param reordered. </b>
<code>s_orig, p, objects</code> ➡️ <code>s, slab, p, objects</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void memcg_slab_free_hook(struct kmem_cache * s, struct slab * slab, void * * p, int objects)
```
</details>
</li>
</ul>
