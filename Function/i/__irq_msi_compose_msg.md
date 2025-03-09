# Function: <code>__irq_msi_compose_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579288336,
      "name": "__irq_msi_compose_msg",
      "external": false,
      "loc": "arch/x86/kernel/apic/msi.c:26",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:irq_msi_update_msg",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288336,
      "name": "__irq_msi_compose_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317808,
      "name": "__irq_msi_compose_msg",
      "external": false,
      "loc": "arch/x86/kernel/apic/msi.c:26",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317808,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301520,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2509",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301520,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304384,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2517",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304384,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2514",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592074415,
      "name": "__irq_msi_compose_msg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579352288,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2522",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593840944,
      "name": "__irq_msi_compose_msg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579414288,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2556",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595965582,
      "name": "__irq_msi_compose_msg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579496688,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2573",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596483205,
      "name": "__irq_msi_compose_msg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579508864,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg, bool dmar)
```

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_msi_compose_msg",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2457",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597379359,
      "name": "__irq_msi_compose_msg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579536912,
      "name": "__irq_msi_compose_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579287040,
      "name": "__irq_msi_compose_msg",
      "external": false,
      "loc": "arch/x86/kernel/apic/msi.c:26",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:irq_msi_update_msg",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287040,
      "name": "__irq_msi_compose_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579222304,
      "name": "__irq_msi_compose_msg",
      "external": false,
      "loc": "arch/x86/kernel/apic/msi.c:26",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:irq_msi_update_msg",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222304,
      "name": "__irq_msi_compose_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579288240,
      "name": "__irq_msi_compose_msg",
      "external": false,
      "loc": "arch/x86/kernel/apic/msi.c:26",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:irq_msi_update_msg",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288240,
      "name": "__irq_msi_compose_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_msi_compose_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294128,
      "name": "__irq_msi_compose_msg",
      "external": false,
      "loc": "arch/x86/kernel/apic/msi.c:26",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:irq_msi_update_msg",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294128,
      "name": "__irq_msi_compose_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg * cfg, struct msi_msg * msg)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dmar</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
