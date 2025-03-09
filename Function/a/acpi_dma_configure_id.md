# Function: <code>acpi_dma_configure_id</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819648,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1526",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819648,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699984,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1529",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699984,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586184528,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1608",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184528,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420336,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1638",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/base/platform.c:platform_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420336,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588677248,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1618",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/base/platform.c:platform_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588677248,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588965920,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1620",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/base/platform.c:platform_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965920,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```

```json
{
  "name": "acpi_dma_configure_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589263424,
      "name": "acpi_dma_configure_id",
      "external": true,
      "loc": "drivers/acpi/scan.c:1627",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/base/platform.c:platform_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589263424,
      "name": "acpi_dma_configure_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int acpi_dma_configure_id(struct device * dev, enum dev_dma_attr attr, const u32 * input_id)
```
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
