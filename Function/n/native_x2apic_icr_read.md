# Function: <code>native_x2apic_icr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211216,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:223",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212384,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:223",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211216,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579212384,
      "name": "native_x2apic_icr_read",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211840,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:230",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213024,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:230",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211840,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579213024,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223536,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:229",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224736,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:229",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223536,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579224736,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221280,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:228",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222496,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:228",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221280,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579222496,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237776,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:244",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579238960,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:244",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237776,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579238960,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250336,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:245",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579251472,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:245",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250336,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579251472,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274144,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:245",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579275280,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:245",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274144,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579275280,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288496,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:247",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579289648,
      "name": "native_x2apic_icr_read",
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
      "addr": 18446744071579288496,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579289648,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291488,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294384,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295616,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291488,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579294384,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579295616,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322160,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579324752,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326800,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322160,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579324752,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579326800,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324848,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326336,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328400,
      "name": "native_x2apic_icr_read",
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
      "addr": 18446744071579324848,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579326336,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579328400,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327568,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329056,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579331104,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327568,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579329056,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579331104,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382224,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579383840,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579386352,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382224,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579383840,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579386352,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447392,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579449280,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579452112,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447392,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579449280,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579452112,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534288,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579536928,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579540320,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534288,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579536928,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579540320,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547200,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579549760,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579552688,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:243",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547200,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579549760,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579552688,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575472,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579577808,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579581392,
      "name": "native_x2apic_icr_read",
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
      "addr": 18446744071579575472,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579577808,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579581392,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate ❓</summary>

```c
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290192,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291424,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290192,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579291424,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226016,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579228176,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226016,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579228176,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291392,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292624,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291392,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579292624,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```

```json
{
  "name": "native_x2apic_icr_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297312,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300224,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301456,
      "name": "native_x2apic_icr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:252",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297312,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579300224,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579301456,
      "name": "native_x2apic_icr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 native_x2apic_icr_read()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 native_x2apic_icr_read()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 native_x2apic_icr_read()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 native_x2apic_icr_read()
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
