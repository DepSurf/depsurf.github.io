# Function: <code>msix_mask_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583384401,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:234",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_set_mask_bit",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583701627,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:240",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583839947,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:240",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583878746,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:221",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584142234,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:221",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584359059,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:221",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584458003,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:221",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void msix_mask_irq(struct msi_desc * desc, u32 flag)
```

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584647184,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:229",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647184,
      "name": "msix_mask_irq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584792478,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585482312,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi.c:pci_msi_mask_irq"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585520929,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:233",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi.c:pci_msi_mask_irq"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585402988,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:204",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_msi_unmask_irq",
        "drivers/pci/msi.c:pci_msi_mask_irq"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497060368,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230270380,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291099792,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275706184,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584741230,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584671998,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584742638,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msix_mask_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584850206,
      "name": "msix_mask_irq",
      "external": false,
      "loc": "drivers/pci/msi.c:230",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:msi_set_mask_bit"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void msix_mask_irq(struct msi_desc * desc, u32 flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void msix_mask_irq(struct msi_desc * desc, u32 flag)
```
</details>
</li>
</ul>
