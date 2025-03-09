# Function: <code>native_apic_msr_eoi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211104,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:190",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212272,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:190",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211104,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579212272,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211728,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:197",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212912,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:197",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211728,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579212912,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223424,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:196",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224624,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:196",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223424,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579224624,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221120,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:195",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222336,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:195",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221120,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579222336,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237664,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:211",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579238848,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:211",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237664,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579238848,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250224,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:212",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579251360,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:212",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250224,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579251360,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274032,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:212",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579275168,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:212",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274032,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579275168,
      "name": "native_apic_msr_eoi_write",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288400,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579289552,
      "name": "native_apic_msr_eoi_write",
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
      "addr": 18446744071579288400,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579289552,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291392,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294288,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295520,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291392,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579294288,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579295520,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320960,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579324208,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325424,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320960,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579324208,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579325424,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323952,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:209",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325760,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:209",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579327024,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:209",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323952,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579325760,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579327024,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326688,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328480,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329744,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326688,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579328480,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579329744,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381168,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579383264,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579384608,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381168,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579383264,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579384608,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445984,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579448480,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579450192,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445984,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579448480,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579450192,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532400,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:208",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579535872,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:208",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579538016,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:208",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532400,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579535872,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579538016,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545312,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579548720,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579550848,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545312,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579548720,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579550848,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290096,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291328,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290096,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579291328,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225424,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226816,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225424,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579226816,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291296,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292528,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291296,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579292528,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```

```json
{
  "name": "native_apic_msr_eoi_write",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297216,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300128,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301360,
      "name": "native_apic_msr_eoi_write",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297216,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579300128,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579301360,
      "name": "native_apic_msr_eoi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
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
void native_apic_msr_eoi_write(u32 reg, u32 v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_apic_msr_eoi_write(u32 reg, u32 v)
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
