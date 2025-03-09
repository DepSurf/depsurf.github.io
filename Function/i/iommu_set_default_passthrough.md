# Function: <code>iommu_set_default_passthrough</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605073593,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586035184,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609361754,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2554",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:platform_optin_force_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776160,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612449660,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2777",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:platform_optin_force_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956960,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614591227,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2763",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586838864,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615548109,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2848",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400000,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617353672,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2625",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710656,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628089399,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2687",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192752,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619855051,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2693",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590514144,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622163899,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2969",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590869440,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511219032,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498837000,
      "name": "iommu_set_default_passthrough",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243864316,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231442316,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302781436,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292052896,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604973216,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796160,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604937517,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655344,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605053916,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985200,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void iommu_set_default_passthrough(bool cmd_line)
```

```json
{
  "name": "iommu_set_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605077787,
      "name": "iommu_set_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2255",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093088,
      "name": "iommu_set_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void iommu_set_default_passthrough(bool cmd_line)
```
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_set_default_passthrough(bool cmd_line)
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
