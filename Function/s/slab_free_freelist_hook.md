# Function: <code>slab_free_freelist_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1337",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1360",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1359",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1361",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1376",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1433",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581567273,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1426",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581632393,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool slab_free_freelist_hook(struct kmem_cache * s, void * * head, void * * tail)
```

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827648,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1477",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827648,
      "name": "slab_free_freelist_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
bool slab_free_freelist_hook(struct kmem_cache * s, void * * head, void * * tail)
```

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875360,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1550",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875360,
      "name": "slab_free_freelist_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
bool slab_free_freelist_hook(struct kmem_cache * s, void * * head, void * * tail)
```

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905776,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1586",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905776,
      "name": "slab_free_freelist_hook",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202624,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1703",
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
      "addr": 18446744071582202624,
      "name": "slab_free_freelist_hook.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582678317,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1757",
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
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583220090,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1784",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free"
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
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583438593,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1795",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free"
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
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583424747,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:2124",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493080876,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226790440,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286525984,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272939680,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581601129,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581542473,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581592441,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "slab_free_freelist_hook",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581658201,
      "name": "slab_free_freelist_hook",
      "external": false,
      "loc": "mm/slub.c:1427",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool slab_free_freelist_hook(struct kmem_cache * s, void * * head, void * * tail)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool slab_free_freelist_hook(struct kmem_cache * s, void * * head, void * * tail)
```
</details>
</li>
</ul>
