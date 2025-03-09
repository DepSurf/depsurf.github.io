# Function: <code>pcc_parse_subspace_irq</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595768878,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:416",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596698818,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:416",
      "file": "drivers/mailbox/pcc.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603029526,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:415",
      "file": "drivers/mailbox/pcc.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603202204,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:406",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605012631,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:406",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605125595,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605165800,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pcc_parse_subspace_irq(int id, struct acpi_pcct_hw_reduced * pcct_ss)
```

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589102063,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102063,
      "name": "pcc_parse_subspace_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int pcc_parse_subspace_irq(int id, struct acpi_pcct_hw_reduced * pcct_ss)
```

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591615059,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615059,
      "name": "pcc_parse_subspace_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614651945,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615610984,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591210146,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:442",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592952721,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:442",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593403317,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:448",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594148773,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:509",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511311580,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605055473,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605021430,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605142147,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "pcc_parse_subspace_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605169994,
      "name": "pcc_parse_subspace_irq",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:397",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pcc_parse_subspace_irq(int id, struct acpi_pcct_hw_reduced * pcct_ss)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int pcc_parse_subspace_irq(int id, struct acpi_pcct_hw_reduced * pcct_ss)
```
</details>
</li>
</ul>
