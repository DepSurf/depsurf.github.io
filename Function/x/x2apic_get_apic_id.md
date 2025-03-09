# Function: <code>x2apic_get_apic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211328,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212480,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211328,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579212480,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211920,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213152,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211920,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579213152,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223616,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224864,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223616,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579224864,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221360,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222624,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:29",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221360,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579222624,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237888,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237888,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250416,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250416,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274224,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274224,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288576,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288576,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292337,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:606",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294464,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292256,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579294464,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321393,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:640",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324352,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321312,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579324352,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324272,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:797",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579325936,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:135",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324272,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579325936,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326992,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:793",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328656,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:135",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326992,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579328656,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381472,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:793",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579383440,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:135",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381472,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579383440,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579446416,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:799",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579448736,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:135",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446416,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579448736,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533008,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:799",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579536240,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:135",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533008,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579536240,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545920,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:800",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579549088,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:138",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545920,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579549088,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u32 x2apic_get_apic_id(u32 id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579577152,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:127",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577152,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290272,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290272,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225520,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225520,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int x2apic_get_apic_id(long unsigned int id)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291472,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291472,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```

```json
{
  "name": "x2apic_get_apic_id",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298176,
      "name": "x2apic_get_apic_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:606",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id"
      ]
    },
    {
      "addr": 18446744071579300304,
      "name": "x2apic_get_apic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:123",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298176,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579300304,
      "name": "x2apic_get_apic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int x</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int id</code> ➡️ <code>u32 id</code>
</li>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
