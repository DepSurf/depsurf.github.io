# Function: <code>unmap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669232,
      "name": "unmap_page_range",
      "external": false,
      "loc": "mm/memory.c:1248",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669232,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1941
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781440,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781440,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2403
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844112,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1280",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844112,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2214
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580889584,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1403",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889584,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2415
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580986160,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1494",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986160,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3311
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581120992,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1506",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120992,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2900
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581199792,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1248",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199792,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3161
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275776,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1217",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275776,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581334576,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334576,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532352,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1250",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532352,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576016,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1424",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576016,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597856,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1442",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597856,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1537",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592199088,
      "name": "unmap_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071581863952,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1623",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593975755,
      "name": "unmap_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071582259600,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1327
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1581",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596031963,
      "name": "unmap_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071582750912,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1309
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1626",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596553905,
      "name": "unmap_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071582967264,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1300
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1653",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597457658,
      "name": "unmap_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071583146176,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1261
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492739128,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492739128,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2512
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226569884,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226569884,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1944
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286094304,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286094304,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1768
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272725110,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272725110,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581303424,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303424,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581247424,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247424,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1048
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294624,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294624,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
void unmap_page_range(struct mmu_gather * tlb, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end, struct zap_details * details)
```

```json
{
  "name": "unmap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581358784,
      "name": "unmap_page_range",
      "external": true,
      "loc": "mm/memory.c:1222",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:unmap_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358784,
      "name": "unmap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
