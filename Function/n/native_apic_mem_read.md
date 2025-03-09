# Function: <code>native_apic_mem_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192247,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:98",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209648,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:98",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214416,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:98",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216086,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:98",
      "file": "arch/x86/kernel/apic/probe_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209648,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579214416,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192614,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210512,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579215008,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210512,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579215008,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579204326,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222176,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226800,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222176,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579226800,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579202150,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219872,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224528,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219872,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579224528,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217654,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236512,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579240256,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236512,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579240256,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024261,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579229942,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249072,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579252784,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249072,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579252784,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028309,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579253638,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272880,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276592,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272880,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579276592,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035861,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579267657,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287216,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290928,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287216,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579290928,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038181,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579270482,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290208,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296912,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290208,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579296912,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049269,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298466,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319744,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326864,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319744,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579326864,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052565,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579303714,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322656,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328448,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322656,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579328448,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057781,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306610,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325392,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579331152,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325392,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579331152,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077477,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579354866,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379904,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579386400,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379904,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579386400,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579105411,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417266,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444464,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579452192,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444464,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579452192,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144387,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579500338,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530528,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579540432,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530528,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579540432,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144921,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579512498,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543424,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579553680,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543424,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579553680,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174713,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:97",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579540947,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:97",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572224,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:97",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579581504,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:97",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572224,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579581504,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038533,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579269186,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288912,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292720,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288912,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579292720,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972813,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579204530,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224176,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579228272,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224176,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579228272,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038117,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579270386,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290112,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293920,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290112,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579293920,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
u32 native_apic_mem_read(u32 reg)
```

```json
{
  "name": "native_apic_mem_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041765,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579275986,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296000,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302752,
      "name": "native_apic_mem_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296000,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579302752,
      "name": "native_apic_mem_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
u32 native_apic_mem_read(u32 reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 native_apic_mem_read(u32 reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 native_apic_mem_read(u32 reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 native_apic_mem_read(u32 reg)
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
