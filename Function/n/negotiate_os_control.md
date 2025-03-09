# Function: <code>negotiate_os_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583588057,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:422",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583910521,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:422",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584051400,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:422",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584111178,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:422",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584381894,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:423",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584604244,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:424",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584701749,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:424",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584902427,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:412",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902427,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585038136,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038136,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585741012,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:413",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741012,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591434509,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591434509,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591375670,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:400",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591375670,
      "name": "negotiate_os_control.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592410965,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:402",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592410965,
      "name": "negotiate_os_control.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594278375,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:613",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594278375,
      "name": "negotiate_os_control.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 841
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:564",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588722128,
      "name": "negotiate_os_control.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2070
    },
    {
      "addr": 18446744071596219294,
      "name": "negotiate_os_control.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:564",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589010256,
      "name": "negotiate_os_control.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2056
    },
    {
      "addr": 18446744071596745830,
      "name": "negotiate_os_control.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:564",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589314608,
      "name": "negotiate_os_control.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2056
    },
    {
      "addr": 18446744071597654478,
      "name": "negotiate_os_control.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497450600,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584977432,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977432,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584886280,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584886280,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989720,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989720,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```

```json
{
  "name": "negotiate_os_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585095896,
      "name": "negotiate_os_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:411",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095896,
      "name": "negotiate_os_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
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
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void negotiate_os_control(struct acpi_pci_root * root, int * no_aspm, bool is_pcie)
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
