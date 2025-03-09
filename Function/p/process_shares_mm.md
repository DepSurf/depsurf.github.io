# Function: <code>process_shares_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580486857,
      "name": "process_shares_mm",
      "external": false,
      "loc": "mm/oom_kill.c:492",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580570418,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:432",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569136,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580636730,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:441",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637456,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580668753,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:446",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669520,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580753782,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:465",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754576,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580892156,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:460",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888352,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580966218,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:481",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962080,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581057486,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059088,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581113242,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114848,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581297143,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:491",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298608,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341076,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:493",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342608,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359572,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:492",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361760,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581607422,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:493",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609008,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581966673,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968960,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582402689,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405136,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582608721,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611152,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780097,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:487",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782720,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492480896,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492483008,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226355204,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226356052,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285766072,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285768768,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272546914,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272547812,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581082090,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083696,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029274,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030880,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581073290,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074896,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```

```json
{
  "name": "process_shares_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134981,
      "name": "process_shares_mm",
      "external": true,
      "loc": "mm/oom_kill.c:490",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:task_will_free_mem"
      ],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136640,
      "name": "process_shares_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool process_shares_mm(struct task_struct * p, struct mm_struct * mm)
```
</details>
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
