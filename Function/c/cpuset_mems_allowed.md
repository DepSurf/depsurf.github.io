# Function: <code>cpuset_mems_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014176,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cpuset.c:2449",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/mempolicy.c:__mpol_dup",
        "mm/migrate.c:SyS_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014176,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046592,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cpuset.c:2470",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/migrate.c:SyS_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046592,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085856,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cpuset.c:2470",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085856,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091632,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:2470",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091632,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144672,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:2474",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144672,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204352,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:2475",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204352,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256656,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3283",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256656,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307568,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3251",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307568,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356432,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356432,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429344,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3341",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429344,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580416880,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3364",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416880,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580419664,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3364",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419664,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580582976,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3446",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582976,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784016,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3492",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784016,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067664,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3797",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067664,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158016,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3989",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158016,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263520,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:4830",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "mm/migrate.c:find_mm_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263520,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491615552,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491615552,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225572464,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225572464,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284608208,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284608208,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272017534,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272017534,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325232,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325232,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272496,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272496,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316480,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316480,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
nodemask_t cpuset_mems_allowed(struct task_struct * tsk)
```

```json
{
  "name": "cpuset_mems_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371360,
      "name": "cpuset_mems_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3339",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371360,
      "name": "cpuset_mems_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
