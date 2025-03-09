# Function: <code>init_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580846048,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:676",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:new_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846048,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972304,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:691",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972304,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581046304,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:690",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046304,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090592,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:692",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090592,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581202816,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:727",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202816,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347840,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:713",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347840,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431952,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:718",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431952,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544592,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544592,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609488,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609488,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824240,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824240,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872208,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:751",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872208,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902816,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:763",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902816,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582197536,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:884",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197536,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661680,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:931",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:init_kmem_cache_nodes",
        "mm/slub.c:setup_object",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661680,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195968,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:998",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:setup_object",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195968,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418864,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:1019",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:setup_object",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418864,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583396096,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:1132",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:setup_object",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583396096,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493052096,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493052096,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226764792,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226764792,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286490848,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286490848,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272922432,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272922432,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578224,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578224,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519792,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519792,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569536,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569536,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_object(struct kmem_cache * s, void * object, u8 val)
```

```json
{
  "name": "init_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634592,
      "name": "init_object",
      "external": false,
      "loc": "mm/slub.c:710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634592,
      "name": "init_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
