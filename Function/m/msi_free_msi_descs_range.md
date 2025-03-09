# Function: <code>msi_free_msi_descs_range</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void msi_free_msi_descs_range(struct device * dev, enum msi_desc_filter filter, unsigned int first_index, unsigned int last_index)
```

```json
{
  "name": "msi_free_msi_descs_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580347904,
      "name": "msi_free_msi_descs_range",
      "external": true,
      "loc": "kernel/irq/msi.c:148",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_free_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs_descs_locked",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_add_simple_msi_descs",
        "drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347904,
      "name": "msi_free_msi_descs_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msi_free_msi_descs_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588244020,
      "name": "msi_free_msi_descs_range",
      "external": false,
      "loc": "include/linux/msi.h:354",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590548816,
      "name": "msi_free_msi_descs_range",
      "external": false,
      "loc": "include/linux/msi.h:354",
      "file": "drivers/base/platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msi_free_msi_descs_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588519565,
      "name": "msi_free_msi_descs_range",
      "external": false,
      "loc": "include/linux/msi.h:358",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590876928,
      "name": "msi_free_msi_descs_range",
      "external": false,
      "loc": "include/linux/msi.h:358",
      "file": "drivers/base/platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msi_free_msi_descs_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588818157,
      "name": "msi_free_msi_descs_range",
      "external": false,
      "loc": "include/linux/msi.h:358",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591220784,
      "name": "msi_free_msi_descs_range",
      "external": false,
      "loc": "include/linux/msi.h:358",
      "file": "drivers/base/platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void msi_free_msi_descs_range(struct device * dev, enum msi_desc_filter filter, unsigned int first_index, unsigned int last_index)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void msi_free_msi_descs_range(struct device * dev, enum msi_desc_filter filter, unsigned int first_index, unsigned int last_index)
```
</details>
</li>
</ul>
