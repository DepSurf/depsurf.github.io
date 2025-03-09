# Function: <code>uprobe_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451760,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1055",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451760,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527184,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1057",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527184,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580590528,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1058",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590528,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620688,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1066",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620688,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701552,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1066",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701552,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833968,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1065",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833968,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1323",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907848,
      "name": "uprobe_mmap.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071580902064,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1311",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005665,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071580999744,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060516,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581054592,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237040,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1362",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237040,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279808,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1362",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279808,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1360",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265671,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581295712,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1361",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188590,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581540640,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1155
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1356",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963688,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581891008,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1174
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324400,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1360",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_expand",
        "mm/mmap.c:vma_expand",
        "mm/mmap.c:vma_expand",
        "mm/mmap.c:vma_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324400,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1210
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525728,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1357",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525728,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1237
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582694640,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1357",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694640,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1237
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492412504,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492412504,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226296192,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226296192,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285678336,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285678336,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1372
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
  "name": "uprobe_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": false,
      "loc": "include/linux/uprobes.h:169",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029364,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581023440,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975444,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071580969536,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020564,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581014640,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int uprobe_mmap(struct vm_area_struct * vma)
```

```json
{
  "name": "uprobe_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_mmap",
      "external": true,
      "loc": "kernel/events/uprobes.c:1363",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081906,
      "name": "uprobe_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581075904,
      "name": "uprobe_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 954
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
int uprobe_mmap(struct vm_area_struct * vma)
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
