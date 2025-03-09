# Function: <code>uv_program_mmr</code>

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
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579469600,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469600,
      "name": "uv_program_mmr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579492112,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492112,
      "name": "uv_program_mmr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579474656,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474656,
      "name": "uv_program_mmr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476720,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476720,
      "name": "uv_program_mmr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void uv_program_mmr(struct irq_cfg * cfg, struct uv_irq_2_mmr_pnode * info)
```

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542336,
      "name": "uv_program_mmr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071592094030,
      "name": "uv_program_mmr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void uv_program_mmr(struct irq_cfg * cfg, struct uv_irq_2_mmr_pnode * info)
```

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631024,
      "name": "uv_program_mmr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071593861552,
      "name": "uv_program_mmr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void uv_program_mmr(struct irq_cfg * cfg, struct uv_irq_2_mmr_pnode * info)
```

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745472,
      "name": "uv_program_mmr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071595972190,
      "name": "uv_program_mmr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void uv_program_mmr(struct irq_cfg * cfg, struct uv_irq_2_mmr_pnode * info)
```

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792016,
      "name": "uv_program_mmr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071596489817,
      "name": "uv_program_mmr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825728,
      "name": "uv_program_mmr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071597386439,
      "name": "uv_program_mmr.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_program_mmr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579474928,
      "name": "uv_program_mmr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_irq.c:27",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474928,
      "name": "uv_program_mmr.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void uv_program_mmr(struct irq_cfg * cfg, struct uv_irq_2_mmr_pnode * info)
```
</details>
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
void uv_program_mmr(struct irq_cfg * cfg, struct uv_irq_2_mmr_pnode * info)
```
</details>
</li>
</ul>
