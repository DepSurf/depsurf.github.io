# Function: <code>atomic_pool_expand</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153456,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:83",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153456,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134480,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134480,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139392,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139392,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283024,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071592150731,
      "name": "atomic_pool_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580455584,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071593923530,
      "name": "atomic_pool_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702368,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071595993695,
      "name": "atomic_pool_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779136,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071596511942,
      "name": "atomic_pool_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
```

```json
{
  "name": "atomic_pool_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "atomic_pool_expand",
      "external": false,
      "loc": "kernel/dma/pool.c:79",
      "file": "kernel/dma/pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/pool.c:__dma_atomic_pool_init",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn",
        "kernel/dma/pool.c:atomic_pool_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867952,
      "name": "atomic_pool_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071597411153,
      "name": "atomic_pool_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int atomic_pool_expand(struct gen_pool * pool, size_t pool_size, gfp_t gfp)
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
