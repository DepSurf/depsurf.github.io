# Function: <code>klp_try_switch_task</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579864673,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:285",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907280,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:310",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907280,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941488,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:298",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941488,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988576,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:298",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988576,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031187,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030272,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081907,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080992,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580141779,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140336,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580119011,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117568,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580122291,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:282",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120704,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580264963,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:282",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263728,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433280,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:289",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433280,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675488,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:289",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675488,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752320,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:314",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752320,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
bool klp_try_switch_task(struct task_struct * task)
```

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837440,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:314",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837440,
      "name": "klp_try_switch_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284207424,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284206032,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
    }
  ]
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
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050643,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049728,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995955,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995040,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580042179,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041264,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_try_switch_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580092963,
      "name": "klp_try_switch_task",
      "external": false,
      "loc": "kernel/livepatch/transition.c:281",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092016,
      "name": "klp_try_switch_task.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool klp_try_switch_task(struct task_struct * task)
```
</details>
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
bool klp_try_switch_task(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool klp_try_switch_task(struct task_struct * task)
```
</details>
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
