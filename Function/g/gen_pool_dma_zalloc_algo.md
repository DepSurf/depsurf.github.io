# Function: <code>gen_pool_dma_zalloc_algo</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181696,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181696,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315392,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315392,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584727603,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727216,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584840835,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:439",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840448,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584885491,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:440",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885104,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311331,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:440",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585310944,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586168642,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:440",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168240,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587163202,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:440",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587162768,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587425856,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425856,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587760912,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:440",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760912,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496203712,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496203712,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229528236,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229528236,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290486816,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290486816,
      "name": "gen_pool_dma_zalloc_algo",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275254304,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275254304,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584284128,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284128,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219328,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219328,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584267040,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267040,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
```

```json
{
  "name": "gen_pool_dma_zalloc_algo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373024,
      "name": "gen_pool_dma_zalloc_algo",
      "external": true,
      "loc": "lib/genalloc.c:438",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_zalloc_align",
        "lib/genalloc.c:gen_pool_dma_zalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373024,
      "name": "gen_pool_dma_zalloc_algo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void * gen_pool_dma_zalloc_algo(struct gen_pool * pool, size_t size, dma_addr_t * dma, genpool_algo_t algo, void * data)
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
