# Function: <code>free_workqueue_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579464560,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:2996",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481360,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498317,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3096",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495168,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514976,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3122",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514976,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506535,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3121",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491600,
      "name": "free_workqueue_attrs.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579503376,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533255,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3135",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518000,
      "name": "free_workqueue_attrs.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579530128,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560823,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3209",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543952,
      "name": "free_workqueue_attrs.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579557680,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598039,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3232",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581200,
      "name": "free_workqueue_attrs.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579594816,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621223,
      "name": "free_workqueue_attrs",
      "external": false,
      "loc": "kernel/workqueue.c:3332",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604832,
      "name": "free_workqueue_attrs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579647303,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630736,
      "name": "free_workqueue_attrs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579644240,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579679330,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3338",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:__padata_set_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675584,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659458,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3344",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:__padata_set_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655408,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665511,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3345",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661872,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579742215,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3384",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739024,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579846650,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3367",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843232,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579986791,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3374",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982944,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039821,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3690",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035520,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082599,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3711",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_affinity_strict_store",
        "kernel/workqueue.c:wq_affinity_strict_store",
        "kernel/workqueue.c:wq_affn_scope_store",
        "kernel/workqueue.c:wq_affn_scope_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076432,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490818292,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq"
      ],
      "caller_func": [
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490815240,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224851784,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq"
      ],
      "caller_func": [
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224850016,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283651352,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq"
      ],
      "caller_func": [
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283647456,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271492944,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq"
      ],
      "caller_func": [
        "kernel/padata.c:padata_setup_cpumasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271490696,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579623607,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607040,
      "name": "free_workqueue_attrs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579620544,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579551975,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535680,
      "name": "free_workqueue_attrs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579548912,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579620887,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604320,
      "name": "free_workqueue_attrs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579617824,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```

```json
{
  "name": "free_workqueue_attrs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579654551,
      "name": "free_workqueue_attrs",
      "external": true,
      "loc": "kernel/workqueue.c:3341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:rcu_free_pool",
        "kernel/workqueue.c:rcu_free_wq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641200,
      "name": "free_workqueue_attrs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579651488,
      "name": "free_workqueue_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void free_workqueue_attrs(struct workqueue_attrs * attrs)
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
