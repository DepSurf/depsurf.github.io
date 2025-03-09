# Function: <code>__ioremap_caller</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579285856,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:83",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_nocache",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285856,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579285568,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:82",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285568,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300960,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:82",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300960,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298736,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:83",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298736,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579319488,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:133",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319488,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:133",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330320,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071579332098,
      "name": "__ioremap_caller.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:133",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356512,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071579358354,
      "name": "__ioremap_caller.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:154",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370720,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071579372866,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375296,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071579377154,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403872,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
    },
    {
      "addr": 18446744071579405997,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404448,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
    },
    {
      "addr": 18446744071591270105,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:178",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407616,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071591212719,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:178",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470224,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071592087015,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:178",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547440,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071593853850,
      "name": "__ioremap_caller.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:179",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652272,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 18446744071595969053,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:184",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666496,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
    },
    {
      "addr": 18446744071596486699,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:184",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701056,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
    },
    {
      "addr": 18446744071597383321,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void * __ioremap_caller(phys_addr_t phys_addr, size_t size, pgprot_t prot, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490343912,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/arm64/mm/ioremap.c:21",
      "file": "arch/arm64/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/ioremap.c:__ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490343912,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * __ioremap_caller(phys_addr_t addr, long unsigned int size, pgprot_t prot, void * caller)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282727488,
      "name": "__ioremap_caller",
      "external": true,
      "loc": "arch/powerpc/mm/ioremap_64.c:57",
      "file": "arch/powerpc/mm/ioremap_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/ioremap.c:ioremap_prot",
        "arch/powerpc/mm/ioremap.c:ioremap_coherent",
        "arch/powerpc/mm/ioremap.c:ioremap_wc",
        "arch/powerpc/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282727488,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271359868,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/riscv/mm/ioremap.c:23",
      "file": "arch/riscv/mm/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/ioremap.c:ioremap"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371200,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071579373058,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301392,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071579303250,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371120,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071579372978,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```

```json
{
  "name": "__ioremap_caller",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ioremap_caller",
      "external": false,
      "loc": "arch/x86/mm/ioremap.c:176",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_prot",
        "arch/x86/mm/ioremap.c:ioremap_cache",
        "arch/x86/mm/ioremap.c:ioremap_encrypted",
        "arch/x86/mm/ioremap.c:ioremap_wt",
        "arch/x86/mm/ioremap.c:ioremap_wc",
        "arch/x86/mm/ioremap.c:ioremap_uc",
        "arch/x86/mm/ioremap.c:ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379600,
      "name": "__ioremap_caller",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071579381458,
      "name": "__ioremap_caller.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool encrypted</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_cache_mode pcm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool encrypted</code>
</li>
<li>
<b>Param type changed. </b>
<code>resource_size_t phys_addr</code> ➡️ <code>phys_addr_t phys_addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t addr</code>
</li>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_cache_mode pcm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool encrypted</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * __ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void * caller, bool encrypted)
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
