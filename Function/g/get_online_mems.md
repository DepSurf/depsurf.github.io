# Function: <code>get_online_mems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875648,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:79",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slub.c:show_slab_objects",
        "mm/memory_hotplug.c:set_online_page_callback",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875648,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003712,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:99",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slub.c:show_slab_objects",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003712,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077632,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:99",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slub.c:show_slab_objects",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077632,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581123727,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:57",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slub.c:show_slab_objects",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124944,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581236335,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:59",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slub.c:show_slab_objects",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237632,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581383589,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:59",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slub.c:show_slab_objects",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383344,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581467813,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:59",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_deactivate_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slub.c:show_slab_objects",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467568,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581583333,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slub.c:show_slab_objects",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583088,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648005,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647760,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581861893,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:59",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865248,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581906069,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:59",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910128,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581753765,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:69",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756688,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582034949,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:134",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/migrate.c:migration_online_cpu",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038016,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582464677,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:151",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/migrate.c:set_migration_target_nodes",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467952,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978517,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:143",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982240,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190037,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:142",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583193888,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583375189,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:210",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378784,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493096264,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493096760,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_online_mems",
      "external": false,
      "loc": "include/linux/memory_hotplug.h:274",
      "file": "mm/slab_common.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286545924,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286547984,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
  "name": "get_online_mems",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_online_mems",
      "external": false,
      "loc": "include/linux/memory_hotplug.h:274",
      "file": "mm/slab_common.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581616741,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616496,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581558069,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557824,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581608053,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607808,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void get_online_mems()
```

```json
{
  "name": "get_online_mems",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581672437,
      "name": "get_online_mems",
      "external": true,
      "loc": "mm/memory_hotplug.c:61",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_shrink_all",
        "mm/slab_common.c:kmem_cache_shrink",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_workfn",
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674208,
      "name": "get_online_mems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void get_online_mems()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void get_online_mems()
```
</details>
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
