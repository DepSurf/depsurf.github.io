# Function: <code>pci_acpi_program_hp_params</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev, const struct hotplug_program_ops * hp_ops)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:398",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554068,
      "name": "pci_acpi_program_hp_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071584552080,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690699,
      "name": "pci_acpi_program_hp_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584688192,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585403536,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403536,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560448,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560448,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438704,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438704,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904320,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:746",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904320,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101088,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:746",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101088,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588292624,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:747",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292624,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588568736,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:747",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588568736,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588868560,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:747",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868560,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496941080,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496941080,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1876
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": false,
      "loc": "drivers/pci/pci.h:660",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": false,
      "loc": "drivers/pci/pci.h:660",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": false,
      "loc": "drivers/pci/pci.h:660",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641179,
      "name": "pci_acpi_program_hp_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584638672,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570955,
      "name": "pci_acpi_program_hp_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584568480,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640859,
      "name": "pci_acpi_program_hp_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584638352,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```

```json
{
  "name": "pci_acpi_program_hp_params",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_acpi_program_hp_params",
      "external": true,
      "loc": "drivers/pci/pci-acpi.c:745",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748555,
      "name": "pci_acpi_program_hp_params.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071584746048,
      "name": "pci_acpi_program_hp_params",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
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
int pci_acpi_program_hp_params(struct pci_dev * dev, const struct hotplug_program_ops * hp_ops)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct hotplug_program_ops * hp_ops</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev * dev)
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
