# Function: <code>native_x2apic_icr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211168,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:218",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212336,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:218",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211168,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579212336,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211792,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:225",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213107,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:225",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211792,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579212976,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223488,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224819,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223488,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579224688,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221232,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:223",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222579,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:223",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221232,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579222448,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579238533,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:239",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240128,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:239",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238736,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579240128,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579250799,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252624,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251136,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579252624,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274831,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276432,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275024,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579276432,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579289199,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290848,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289408,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579290848,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293136,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295312,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296832,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293136,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579295232,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579296832,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322112,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325184,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326752,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322112,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579325056,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579326752,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324800,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:237",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326819,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:237",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328352,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:237",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324800,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579326640,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579328352,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327520,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329539,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331056,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327520,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579329088,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579331056,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382176,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579384403,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386304,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382176,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579383872,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579386304,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579447328,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579449907,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452048,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447328,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579449328,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579452048,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579534208,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:236",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579537763,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:236",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540240,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:236",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534208,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579536992,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579540240,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547120,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579550499,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552608,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:238",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547120,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579549824,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579552608,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575392,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579578083,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581312,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575392,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579577872,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579581312,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579291120,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292640,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291040,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579292640,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579226378,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228112,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226480,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579228112,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292320,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293840,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292240,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579293840,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```

```json
{
  "name": "native_x2apic_icr_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298976,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301152,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302672,
      "name": "native_x2apic_icr_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298976,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579301072,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579302672,
      "name": "native_x2apic_icr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_x2apic_icr_write(u32 low, u32 id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id)
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
