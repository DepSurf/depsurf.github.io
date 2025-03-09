# Function: <code>is_ISA_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 s, u64 e)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054608,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820.h:60",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820.h:60",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054608,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 s, u64 e)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579050976,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820.h:60",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820.h:60",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050976,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 s, u64 e)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579050080,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820.h:66",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820.h:66",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050080,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042464,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:46",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:46",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042464,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051568,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:49",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051568,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056464,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:49",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056464,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061424,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:49",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061424,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069456,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069456,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579071456,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291525,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071456,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579079312,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579321141,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579079312,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081552,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579324053,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081552,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579088416,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326789,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088416,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111552,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579381269,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111552,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143168,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579446149,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143168,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579187744,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579532629,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187744,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191808,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579545541,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191808,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221056,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579574117,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221056,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071808,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071808,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579004704,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579004704,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071392,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071392,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool is_ISA_range(u64 start, u64 end)
```

```json
{
  "name": "is_ISA_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579075488,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/x86_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579297349,
      "name": "is_ISA_range",
      "external": false,
      "loc": "arch/x86/include/asm/e820/api.h:50",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075488,
      "name": "is_ISA_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 start</code>
</li>
<li>
<b>Param added. </b>
<code>u64 end</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 s</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 e</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool is_ISA_range(u64 start, u64 end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool is_ISA_range(u64 start, u64 end)
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
