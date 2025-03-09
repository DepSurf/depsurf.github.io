# Function: <code>raw_pci_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161728,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161728,
      "name": "raw_pci_read",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574928,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574928,
      "name": "raw_pci_read",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756480,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756480,
      "name": "raw_pci_read",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586883328,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:39",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883328,
      "name": "raw_pci_read",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587371984,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:39",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371984,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587675808,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:39",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587675808,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807104,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:39",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807104,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588112592,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588112592,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318288,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318288,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591138684,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591138752,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591222892,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591222960,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591172140,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591172208,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592025596,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592025664,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593792332,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593792448,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595735116,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595735408,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596261052,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261344,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597143660,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:41",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597143952,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490318528,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/arm64/kernel/pci.c:37",
      "file": "arch/arm64/kernel/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490318528,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587921936,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921936,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637904,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637904,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255344,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255344,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```

```json
{
  "name": "raw_pci_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390864,
      "name": "raw_pci_read",
      "external": true,
      "loc": "arch/x86/pci/common.c:40",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/numachip.c:pci_numachip_init",
        "arch/x86/pci/common.c:pci_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390864,
      "name": "raw_pci_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 * val)
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
