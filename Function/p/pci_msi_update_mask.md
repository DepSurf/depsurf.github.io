# Function: <code>pci_msi_update_mask</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_msi_update_mask(struct msi_desc * desc, u32 clear, u32 set)
```

```json
{
  "name": "pci_msi_update_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585857968,
      "name": "pci_msi_update_mask",
      "external": false,
      "loc": "drivers/pci/msi.c:146",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi.c:pci_msi_mask_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857968,
      "name": "pci_msi_update_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void pci_msi_update_mask(struct msi_desc * desc, u32 clear, u32 set)
```

```json
{
  "name": "pci_msi_update_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587051488,
      "name": "pci_msi_update_mask",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:19",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi/msi.c:pci_msi_mask_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051488,
      "name": "pci_msi_update_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void pci_msi_update_mask(struct msi_desc * desc, u32 clear, u32 set)
```

```json
{
  "name": "pci_msi_update_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588239362,
      "name": "pci_msi_update_mask",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:110",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:pci_msi_mask_irq"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi",
        "drivers/pci/msi/irqdomain.c:pci_irq_mask_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588236688,
      "name": "pci_msi_update_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void pci_msi_update_mask(struct msi_desc * desc, u32 clear, u32 set)
```

```json
{
  "name": "pci_msi_update_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588514866,
      "name": "pci_msi_update_mask",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:110",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:pci_msi_mask_irq"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi",
        "drivers/pci/msi/irqdomain.c:pci_irq_mask_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588512192,
      "name": "pci_msi_update_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void pci_msi_update_mask(struct msi_desc * desc, u32 clear, u32 set)
```

```json
{
  "name": "pci_msi_update_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588813458,
      "name": "pci_msi_update_mask",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:111",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:pci_msi_mask_irq"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/pci/msi/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi",
        "drivers/pci/msi/irqdomain.c:pci_irq_mask_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588810784,
      "name": "pci_msi_update_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void pci_msi_update_mask(struct msi_desc * desc, u32 clear, u32 set)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
