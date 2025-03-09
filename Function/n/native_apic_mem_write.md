# Function: <code>native_apic_mem_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192278,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:89",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209632,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:89",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214400,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:89",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216133,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:89",
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
      "addr": 18446744071579209632,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579214400,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192629,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:94",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210496,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:94",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214992,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:94",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210496,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579214992,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579204341,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:93",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222160,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:93",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226784,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:93",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222160,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579226784,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579202165,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:92",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219856,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:92",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224512,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:92",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219856,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579224512,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217669,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236496,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579240240,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579236496,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579240240,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024333,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579229957,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249056,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579252768,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579249056,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579252768,
      "name": "native_apic_mem_write",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028381,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579253653,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272864,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:102",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276576,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579272864,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579276576,
      "name": "native_apic_mem_write",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035933,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579267672,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287200,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290912,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579287200,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579290912,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038253,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579270500,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290192,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296896,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579290192,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579296896,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049341,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298484,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319728,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326848,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579319728,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579326848,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052637,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579303732,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322640,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328432,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579322640,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579328432,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057853,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306628,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325376,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579331136,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579325376,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579331136,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077549,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579354884,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379888,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579386384,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579379888,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579386384,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579105567,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417284,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444432,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579452160,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579444432,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579452160,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144559,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579500356,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530480,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:101",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579540384,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579530480,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579540384,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579145081,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579512516,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543376,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579553632,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579543376,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579553632,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174873,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:88",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579540965,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:88",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572256,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:88",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:native_apic_mem_eoi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581536,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:88",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:native_apic_mem_eoi"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572176,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579581456,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038605,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579269204,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288896,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292704,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579288896,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579292704,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972925,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579204548,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224160,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579228256,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579224160,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579228256,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038189,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579270404,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290096,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293904,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579290096,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579293904,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_mem_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041837,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276004,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field",
        "arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295984,
      "name": "native_apic_mem_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:103",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302736,
      "name": "native_apic_mem_write",
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
      "addr": 18446744071579295984,
      "name": "native_apic_mem_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579302736,
      "name": "native_apic_mem_write",
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
void native_apic_mem_write(u32 reg, u32 v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_apic_mem_write(u32 reg, u32 v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_apic_mem_write(u32 reg, u32 v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_apic_mem_write(u32 reg, u32 v)
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
