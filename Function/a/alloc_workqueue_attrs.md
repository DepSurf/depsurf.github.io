# Function: <code>alloc_workqueue_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481392,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3013",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481392,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495200,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3113",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495200,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515344,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3139",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515344,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503408,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3138",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503408,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530160,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3152",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530160,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3226",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566735,
      "name": "alloc_workqueue_attrs.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579557712,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct workqueue_attrs * alloc_workqueue_attrs(gfp_t gfp_mask)
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3249",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603919,
      "name": "alloc_workqueue_attrs.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579594848,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": false,
      "loc": "kernel/workqueue.c:3348",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608608,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071579627401,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653411,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579644272,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3354",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:__padata_set_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685070,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579675632,
      "name": "alloc_workqueue_attrs",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3360",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:__padata_set_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591280431,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579655456,
      "name": "alloc_workqueue_attrs",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3361",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223372,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579661920,
      "name": "alloc_workqueue_attrs",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3400",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592104531,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579739072,
      "name": "alloc_workqueue_attrs",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3383",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593872265,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579843296,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983024,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3390",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983024,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035600,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3706",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035600,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076512,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3728",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_affinity_strict_store",
        "kernel/workqueue.c:wq_affn_scope_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076512,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490815288,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490815288,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224850052,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224850052,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283647520,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283647520,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271490740,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271490740,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629715,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579620576,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558067,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579548944,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626995,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579617856,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct workqueue_attrs * alloc_workqueue_attrs()
```

```json
{
  "name": "alloc_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:init_worker_pool",
        "kernel/workqueue.c:workqueue_init",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660638,
      "name": "alloc_workqueue_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579651520,
      "name": "alloc_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
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
