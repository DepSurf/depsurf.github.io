# Function: <code>__default_send_IPI_shortcut</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579215252,
      "name": "__default_send_IPI_shortcut",
      "external": false,
      "loc": "arch/x86/include/asm/ipi.h:61",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579216086,
      "name": "__default_send_IPI_shortcut",
      "external": false,
      "loc": "arch/x86/include/asm/ipi.h:61",
      "file": "arch/x86/kernel/apic/probe_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192528,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:20",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192528,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204240,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:20",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204240,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202064,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:20",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202064,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217568,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:21",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217568,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229856,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:21",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229856,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253552,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:21",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253552,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267568,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:21",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267568,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270469,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269680,
      "name": "__default_send_IPI_shortcut",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298453,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297664,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579303701,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302912,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306597,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305776,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354853,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353856,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417253,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416224,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579500325,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499152,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579512485,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:111",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511328,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579540933,
      "name": "__default_send_IPI_shortcut",
      "external": false,
      "loc": "arch/x86/kernel/apic/ipi.c:152",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579269173,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268384,
      "name": "__default_send_IPI_shortcut",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579204517,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203808,
      "name": "__default_send_IPI_shortcut",
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270373,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269584,
      "name": "__default_send_IPI_shortcut",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```

```json
{
  "name": "__default_send_IPI_shortcut",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275973,
      "name": "__default_send_IPI_shortcut",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:110",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_self",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_all",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275184,
      "name": "__default_send_IPI_shortcut",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int dest</code>
</li>
</ul>
</details>
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector)
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
