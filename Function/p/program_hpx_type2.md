# Function: <code>program_hpx_type2</code>

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
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584689367,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399152,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    },
    {
      "addr": 18446744071585404515,
      "name": "program_hpx_type2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555840,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
    },
    {
      "addr": 18446744071591403526,
      "name": "program_hpx_type2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434160,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
    },
    {
      "addr": 18446744071591345757,
      "name": "program_hpx_type2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:284",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899600,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071592372764,
      "name": "program_hpx_type2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:284",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097840,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071594236195,
      "name": "program_hpx_type2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288960,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:285",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288960,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564864,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:285",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564864,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588864688,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:285",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_run_hpx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588864688,
      "name": "program_hpx_type2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496942228,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params"
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
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584639847,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params"
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
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584569655,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params"
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
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584639527,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params"
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
  "name": "program_hpx_type2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584747223,
      "name": "program_hpx_type2",
      "external": false,
      "loc": "drivers/pci/pci-acpi.c:283",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params"
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
void program_hpx_type2(struct pci_dev * dev, struct hpx_type2 * hpx)
```
</details>
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
