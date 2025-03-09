# Function: <code>uprobe_munmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452496,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1110",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452496,
      "name": "uprobe_munmap",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527920,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1112",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527920,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591248,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1113",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591248,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621328,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1121",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621328,
      "name": "uprobe_munmap",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702192,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1121",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702192,
      "name": "uprobe_munmap",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834608,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1120",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834608,
      "name": "uprobe_munmap",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902992,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1386",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902992,
      "name": "uprobe_munmap",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000704,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1374",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000704,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055552,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055552,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237488,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1425",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237488,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280256,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1425",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280256,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296736,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1423",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296736,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541808,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1424",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541808,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892192,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1419",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892192,
      "name": "uprobe_munmap",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582325632,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1423",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_expand",
        "mm/mmap.c:vma_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325632,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526992,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1420",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:vma_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526992,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582695904,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1420",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:vma_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695904,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492413528,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492413528,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226297280,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226297280,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285679712,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285679712,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_munmap",
      "external": false,
      "loc": "include/linux/uprobes.h:174",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uprobe_munmap",
      "external": false,
      "loc": "include/linux/uprobes.h:174",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024400,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024400,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970496,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970496,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015600,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015600,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "uprobe_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076864,
      "name": "uprobe_munmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1426",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_single_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076864,
      "name": "uprobe_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void uprobe_munmap(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
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
