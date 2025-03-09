# Function: <code>kmem_cache_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580867024,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1212",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867024,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995168,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1257",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995168,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068992,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1256",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068992,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581119964,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1258",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094496,
      "name": "kmem_cache_flags.part.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071581117232,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
slab_flags_t kmem_cache_flags(long unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581232348,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1293",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206752,
      "name": "kmem_cache_flags.part.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071581229616,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581368437,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1281",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351024,
      "name": "kmem_cache_flags.part.78",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071581374112,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457056,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1308",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457056,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571312,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1303",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571312,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636528,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636528,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853680,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1349",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853680,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902256,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1410",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902256,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932848,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1421",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932848,
      "name": "kmem_cache_flags",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231680,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1550",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231680,
      "name": "kmem_cache_flags",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582700832,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1603",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700832,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224016,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1639",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224016,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442640,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1652",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442640,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428608,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1776",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428608,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493085312,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493085312,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226792624,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226792624,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286532032,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286532032,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272943390,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272943390,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605264,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605264,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546608,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546608,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596576,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596576,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char * name, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662432,
      "name": "kmem_cache_flags",
      "external": true,
      "loc": "mm/slub.c:1304",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:find_mergeable",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662432,
      "name": "kmem_cache_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>slab_flags_t flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>slab_flags_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int object_size</code> ➡️ <code>unsigned int object_size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*)(void *) ctor</code>
</li>
</ul>
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
