# Function: <code>native_apic_msr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595037116,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:195",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211584,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:195",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213552,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:195",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211584,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579213552,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595202761,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:202",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212192,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:202",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214304,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:202",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212192,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579214304,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595445663,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:201",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223888,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:201",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225904,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:201",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223888,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579225904,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596366418,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:200",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221152,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:200",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222368,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:200",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221152,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579222368,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602684845,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:216",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237696,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:216",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579238880,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:216",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237696,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579238880,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602856283,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:217",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250256,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:217",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579251392,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:217",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250256,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579251392,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604653214,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:217",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274064,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:217",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579275200,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:217",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274064,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579275200,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604752263,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288416,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579289568,
      "name": "native_apic_msr_read",
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
      "addr": 18446744071579288416,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579289568,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604765668,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291408,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294304,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295536,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291408,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579294304,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579295536,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609111975,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320976,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579324224,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325440,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320976,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579324224,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579325440,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612176699,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323968,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325776,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:214",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579327040,
      "name": "native_apic_msr_read",
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
      "addr": 18446744071579323968,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579325776,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579327040,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614316950,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326704,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328496,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329760,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326704,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579328496,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579329760,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615245602,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381184,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579383280,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579384624,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381184,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579383280,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579384624,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617021991,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446016,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579448512,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579450224,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446016,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579448512,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579450224,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627656887,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:213",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532448,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:213",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579535920,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:213",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579538064,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:213",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532448,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579535920,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579538064,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619413831,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545360,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579548768,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579550896,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:215",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545360,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579548768,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579550896,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621709431,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:203",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id",
        "arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574000,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:203",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579577040,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:203",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579578832,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:203",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574000,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579577040,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579578832,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604691947,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290112,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291344,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290112,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579291344,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604659468,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225632,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579227072,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225632,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579227072,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604769531,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291312,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292544,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291312,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579292544,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```

```json
{
  "name": "native_apic_msr_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604769788,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297232,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300144,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301376,
      "name": "native_apic_msr_read",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:224",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297232,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579300144,
      "name": "native_apic_msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579301376,
      "name": "native_apic_msr_read",
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
u32 native_apic_msr_read(u32 reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 native_apic_msr_read(u32 reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 native_apic_msr_read(u32 reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 native_apic_msr_read(u32 reg)
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
