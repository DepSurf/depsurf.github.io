# Function: <code>on_each_cpu_cond</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910000,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:665",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:validate_store",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_create",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910000,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939712,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:650",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939712,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970832,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:657",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970832,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976224,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:668",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976224,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022672,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:670",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022672,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076752,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:672",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076752,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124384,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:704",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124384,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169872,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169872,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217808,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217808,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285504,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:778",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285504,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269024,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:915",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269024,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
  "name": "on_each_cpu_cond",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581915579,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440101,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_bh_lrus"
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
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582762933,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_bh_lrus"
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
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583312805,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_bh_lrus"
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
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583898565,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_bh_lrus"
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
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584122053,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_bh_lrus"
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
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584338741,
      "name": "on_each_cpu_cond",
      "external": false,
      "loc": "include/linux/smp.h:102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_bh_lrus"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491456680,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491456680,
      "name": "on_each_cpu_cond",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225443144,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225443144,
      "name": "on_each_cpu_cond",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284407664,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284407664,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271912286,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271912286,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186608,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186608,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134048,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134048,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178080,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178080,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void on_each_cpu_cond(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags)
```

```json
{
  "name": "on_each_cpu_cond",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230320,
      "name": "on_each_cpu_cond",
      "external": true,
      "loc": "kernel/smp.c:717",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230320,
      "name": "on_each_cpu_cond",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>bool (*)(int, void *) cond_func</code> ➡️ <code>smp_cond_func_t cond_func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void on_each_cpu_cond(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait)
```
</details>
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
