# Function: <code>rhashtable_rehash_alloc</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583480064,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:386",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480064,
      "name": "rhashtable_rehash_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583661040,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:386",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583661040,
      "name": "rhashtable_rehash_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877952,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:356",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877952,
      "name": "rhashtable_rehash_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961360,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:344",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961360,
      "name": "rhashtable_rehash_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584141056,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141056,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584263504,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263504,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584674385,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:351",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rhashtable_shrink"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584792078,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:351",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584836070,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:351",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585255251,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:351",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586098431,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:351",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587082175,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:354",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587340847,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:354",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587624319,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:354",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496145608,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496145608,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229468240,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229468240,
      "name": "rhashtable_rehash_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290405936,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290405936,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275201032,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275201032,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584232240,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232240,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584167440,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167440,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584216000,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216000,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_rehash_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584320992,
      "name": "rhashtable_rehash_alloc",
      "external": false,
      "loc": "lib/rhashtable.c:342",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320992,
      "name": "rhashtable_rehash_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int rhashtable_rehash_alloc(struct rhashtable * ht, struct bucket_table * old_tbl, unsigned int size)
```
</details>
</li>
</ul>
