# Function: <code>__send_ipi_mask_ex</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579024737,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:94",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579028824,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:95",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579036032,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036032,
      "name": "__send_ipi_mask_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038352,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038352,
      "name": "__send_ipi_mask_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049563,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047872,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052836,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051200,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579058052,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056384,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579079141,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077568,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071592050495,
      "name": "__send_ipi_mask_ex.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579107474,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105616,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
    },
    {
      "addr": 18446744071593817041,
      "name": "__send_ipi_mask_ex.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144898,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142688,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579145506,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:107",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143344,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174037,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:107",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172720,
      "name": "__send_ipi_mask_ex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038704,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038704,
      "name": "__send_ipi_mask_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578971549,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038288,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038288,
      "name": "__send_ipi_mask_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041936,
      "name": "__send_ipi_mask_ex",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:100",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041936,
      "name": "__send_ipi_mask_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
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
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
