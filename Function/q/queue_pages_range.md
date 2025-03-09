# Function: <code>queue_pages_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810576,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:634",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810576,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935056,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:666",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935056,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003808,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:668",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003808,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051040,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:602",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051040,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162208,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:644",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162208,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305936,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:619",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305936,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388864,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:645",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388864,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500592,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:672",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500592,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581581439,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581793920,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:742",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581841686,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:742",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581872531,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:742",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164353,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:723",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582621383,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:727",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583145717,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:728",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist, bool lock_vma)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583338848,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:747",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334304,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
long int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570304,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:726",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570304,
      "name": "queue_pages_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493019304,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286446808,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581550175,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491823,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541487,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
  "name": "queue_pages_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581606608,
      "name": "queue_pages_range",
      "external": false,
      "loc": "mm/mempolicy.c:680",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node"
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int queue_pages_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, nodemask_t * nodes, long unsigned int flags, struct list_head * pagelist, bool lock_vma)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool lock_vma</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
</ul>
