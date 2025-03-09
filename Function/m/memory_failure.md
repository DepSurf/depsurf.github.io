# Function: <code>memory_failure</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int trapno, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951536,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1068",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "mm/madvise.c:SyS_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:store_hard_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951536,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2899
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
int memory_failure(long unsigned int pfn, int trapno, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100128,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1031",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "mm/madvise.c:SyS_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:store_hard_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100128,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3662
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
int memory_failure(long unsigned int pfn, int trapno, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175344,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1029",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "mm/madvise.c:SyS_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:store_hard_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175344,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3590
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
int memory_failure(long unsigned int pfn, int trapno, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225680,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1123",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "mm/madvise.c:SyS_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:store_hard_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225680,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1598
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
int memory_failure(long unsigned int pfn, int trapno, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356576,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1123",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "mm/madvise.c:SyS_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:store_hard_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356576,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1703
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1247",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:store_hard_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510307,
      "name": "memory_failure.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071581504832,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1901
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581590889,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1251",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596170,
      "name": "memory_failure.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071581590416,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1244",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702944,
      "name": "memory_failure.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1418
    },
    {
      "addr": 18446744071581707601,
      "name": "memory_failure.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581707794,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581704368,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781185,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581777280,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1965
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1271",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002858,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071581998896,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1297
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1397",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591338587,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071582049712,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1463",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281268,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071582075776,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1065
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1602",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592227584,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071582387200,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1071
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1758",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_never",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594006521,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071582892784,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1891
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445696,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:2007",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445696,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2430
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666016,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:2135",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_never",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/madvise.c:do_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666016,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2113
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860256,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:2185",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_never",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "mm/madvise.c:do_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860256,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2297
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493232920,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493232920,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2324
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286755040,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/mce.c:machine_process_ue_event",
        "arch/powerpc/platforms/powernv/opal-memory-errors.c:mem_error_handler",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286755040,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3412
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749921,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581746016,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1965
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688545,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581684640,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1965
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741233,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581737328,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1965
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
int memory_failure(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure",
      "external": true,
      "loc": "mm/memory-failure.c:1248",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memory-failure.c:memory_failure_work_func",
        "drivers/base/memory.c:hard_offline_page_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809489,
      "name": "memory_failure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071581805568,
      "name": "memory_failure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1975
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapno</code>
</li>
<li>
<b>Param reordered. </b>
<code>pfn, trapno, flags</code> ➡️ <code>pfn, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int memory_failure(long unsigned int pfn, int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int memory_failure(long unsigned int pfn, int flags)
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
