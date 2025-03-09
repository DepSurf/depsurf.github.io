# Function: <code>mem_cgroup_from_obj</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757136,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757136,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976560,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2678",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976560,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026448,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2964",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/memcontrol.c:__mod_lruvec_kmem_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026448,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052880,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2796",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/memcontrol.c:__mod_lruvec_kmem_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052880,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2864",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/memcontrol.c:__mod_lruvec_kmem_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592225550,
      "name": "mem_cgroup_from_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071582359680,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2857",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/memcontrol.c:__mod_lruvec_kmem_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004627,
      "name": "mem_cgroup_from_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582856256,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2965",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596048860,
      "name": "mem_cgroup_from_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583403024,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2975",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571334,
      "name": "mem_cgroup_from_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583623312,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:3090",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597475823,
      "name": "mem_cgroup_from_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583818320,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493210752,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493210752,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226841056,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226841056,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286720528,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286720528,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272987412,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272987412,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725872,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725872,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664672,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664672,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717184,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717184,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```

```json
{
  "name": "mem_cgroup_from_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784864,
      "name": "mem_cgroup_from_obj",
      "external": true,
      "loc": "mm/memcontrol.c:2798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_obj_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784864,
      "name": "mem_cgroup_from_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct mem_cgroup * mem_cgroup_from_obj(void * p)
```
</details>
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
