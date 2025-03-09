# Function: <code>raw_pci_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161840,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161840,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575040,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575040,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756592,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756592,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586883440,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:49",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883440,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587372096,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:49",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372096,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587675920,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:49",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587675920,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807216,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:49",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807216,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588112704,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588112704,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318400,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318400,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591138588,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591138816,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591222796,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223024,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591172044,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591172272,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592025500,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592025728,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593792188,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593792560,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595735276,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595735536,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596261212,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261472,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597143820,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:51",
      "file": "arch/x86/pci/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_write"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597144080,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490318672,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/arm64/kernel/pci.c:47",
      "file": "arch/arm64/kernel/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490318672,
      "name": "raw_pci_write",
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587922048,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922048,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587638016,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638016,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255456,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255456,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```

```json
{
  "name": "raw_pci_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390976,
      "name": "raw_pci_write",
      "external": true,
      "loc": "arch/x86/pci/common.c:50",
      "file": "arch/x86/pci/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_pci_configuration",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/common.c:pci_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390976,
      "name": "raw_pci_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val)
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
