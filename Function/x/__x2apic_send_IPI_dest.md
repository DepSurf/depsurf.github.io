# Function: <code>__x2apic_send_IPI_dest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579211913,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213098,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579212336,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ]
    },
    {
      "addr": 18446744071579213088,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212336,
      "name": "__x2apic_send_IPI_dest.constprop.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579213088,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224032,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ]
    },
    {
      "addr": 18446744071579224800,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224032,
      "name": "__x2apic_send_IPI_dest.constprop.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579224800,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221744,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ]
    },
    {
      "addr": 18446744071579222560,
      "name": "__x2apic_send_IPI_dest",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:23",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221744,
      "name": "__x2apic_send_IPI_dest.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579222560,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579238533,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:114",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238784,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579250799,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:114",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251264,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274831,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:114",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275072,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579289199,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:114",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289456,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579295087,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295376,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324911,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325280,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326498,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326912,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579329264,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329632,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384057,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384496,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449527,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450032,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579537370,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537824,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550202,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550656,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578266,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:110",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578688,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579290895,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291184,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579226190,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226640,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292095,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292384,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```

```json
{
  "name": "__x2apic_send_IPI_dest",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300927,
      "name": "__x2apic_send_IPI_dest",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301216,
      "name": "__x2apic_send_IPI_dest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __x2apic_send_IPI_dest(unsigned int apicid, int vector, unsigned int dest)
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
