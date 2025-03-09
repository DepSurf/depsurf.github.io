# Function: <code>put_css_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_css_set(struct css_set * cset)
```

```json
{
  "name": "put_css_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979072,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup.c:795",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_free",
        "kernel/cgroup.c:copy_cgroup_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979072,
      "name": "put_css_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void put_css_set(struct css_set * cset)
```

```json
{
  "name": "put_css_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580005712,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup.c:838",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/cgroup.c:cgroup_free",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005712,
      "name": "put_css_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void put_css_set(struct css_set * cset)
```

```json
{
  "name": "put_css_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039312,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup.c:841",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/cgroup.c:cgroup_free",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039312,
      "name": "put_css_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580059709,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:132",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580061492,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:132",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580110483,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:133",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580113870,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:133",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580169686,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:133",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580173523,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:133",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580217606,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:161",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221411,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:161",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580266004,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270326,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580314308,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318486,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580384372,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390510,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580371316,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580377507,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580374324,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580380430,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580535460,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:199",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542350,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:199",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580732787,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580740096,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:198",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581008659,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:196",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016704,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:196",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097251,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:196",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105127,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:196",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581194675,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:196",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202935,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:196",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_css_set(struct css_set * cset)
```

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491567244,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:find_css_set"
      ]
    },
    {
      "addr": 18446603336491574328,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491541200,
      "name": "put_css_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225531636,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3225537660,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284546212,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284553444,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271980664,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271985390,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580283108,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287286,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580230516,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234656,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580274356,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580278534,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_css_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580327892,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580332400,
      "name": "put_css_set",
      "external": false,
      "loc": "kernel/cgroup/cgroup-internal.h:180",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void put_css_set(struct css_set * cset)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void put_css_set(struct css_set * cset)
```
</details>
</li>
</ul>
