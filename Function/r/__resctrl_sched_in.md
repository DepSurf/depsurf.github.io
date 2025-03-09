# Function: <code>__resctrl_sched_in</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579031765,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198144,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198144,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579039398,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211904,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211904,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041798,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214192,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214192,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050880,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ]
    },
    {
      "addr": 18446744071579235376,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050880,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071579235376,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053536,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ]
    },
    {
      "addr": 18446744071579227968,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053536,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071579227968,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579062232,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230320,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230320,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579083496,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269136,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269136,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579112256,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321760,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321760,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579150992,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:52",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405874,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:52",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
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
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153104,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:52",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417906,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:52",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid"
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
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579182400,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:52",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436828,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl.h:52",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042150,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213040,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213040,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975169,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152240,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152240,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041734,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214112,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214112,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __resctrl_sched_in()
```

```json
{
  "name": "__resctrl_sched_in",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579045398,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218624,
      "name": "__resctrl_sched_in",
      "external": false,
      "loc": "arch/x86/include/asm/resctrl_sched.h:54",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218624,
      "name": "__resctrl_sched_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __resctrl_sched_in()
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __resctrl_sched_in()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __resctrl_sched_in()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __resctrl_sched_in()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __resctrl_sched_in()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __resctrl_sched_in()
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
