# Function: <code>x2apic_send_IPI_self</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211392,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212544,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211392,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579212544,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211984,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213216,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211984,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579213216,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223680,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224928,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223680,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579224928,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221424,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222688,
      "name": "x2apic_send_IPI_self",
      "external": false,
      "loc": "arch/x86/include/asm/x2apic.h:44",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221424,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579222688,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237952,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579237952,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250480,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579250480,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274288,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579274288,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288640,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579288640,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294528,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579294528,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324416,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579324416,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326000,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:150",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326000,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579328720,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:150",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328720,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383472,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:150",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383472,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448800,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:150",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448800,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536336,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:150",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536336,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549184,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:153",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549184,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577200,
      "name": "x2apic_send_IPI_self",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:105",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577200,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290336,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579290336,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225584,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579225584,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291536,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579291536,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector)
```

```json
{
  "name": "x2apic_send_IPI_self",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300368,
      "name": "x2apic_send_IPI_self",
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
      "addr": 18446744071579300368,
      "name": "x2apic_send_IPI_self",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void x2apic_send_IPI_self(int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void x2apic_send_IPI_self(int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void x2apic_send_IPI_self(int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void x2apic_send_IPI_self(int vector)
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
