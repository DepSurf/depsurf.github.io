# Function: <code>bpf_lru_pop_free</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580509728,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:497",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509728,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539392,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:497",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539392,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1271
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603840,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:497",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603840,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1345
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699472,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:497",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699472,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1336
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772160,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:497",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772160,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1347
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857712,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857712,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908752,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908752,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055952,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055952,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068112,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068112,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082704,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082704,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186469,
      "name": "bpf_lru_pop_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581311136,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960771,
      "name": "bpf_lru_pop_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581610272,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021398,
      "name": "bpf_lru_pop_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581994096,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:499",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543025,
      "name": "bpf_lru_pop_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582185424,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:499",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597446118,
      "name": "bpf_lru_pop_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582334192,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492238768,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492238768,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1740
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226134448,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226134448,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285467024,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285467024,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272384896,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272384896,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877552,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877552,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823616,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823616,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868800,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868800,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```

```json
{
  "name": "bpf_lru_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927376,
      "name": "bpf_lru_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:494",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_lru_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927376,
      "name": "bpf_lru_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct bpf_lru_node * bpf_lru_pop_free(struct bpf_lru * lru, u32 hash)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
