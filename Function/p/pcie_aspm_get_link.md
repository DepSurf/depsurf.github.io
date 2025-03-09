# Function: <code>pcie_aspm_get_link</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584718640,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718640,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585378693,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1070",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled"
      ],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371728,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585536469,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1062",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled"
      ],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531424,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585412549,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1062",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled"
      ],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409792,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874709,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1062",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_capable",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled"
      ],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871872,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587068021,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1098",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_capable",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
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
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588253333,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1060",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_capable",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
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
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588528677,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1024",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_capable",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:pci_enable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
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
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588831381,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1049",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:l1_2_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_1_pcipm_show",
        "drivers/pci/pcie/aspm.c:l1_2_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_1_aspm_show",
        "drivers/pci/pcie/aspm.c:l1_aspm_show",
        "drivers/pci/pcie/aspm.c:l0s_aspm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_capable",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_enable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496977920,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496977920,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230241840,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230241840,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275645684,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275645684,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669120,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669120,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584598272,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598272,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668800,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668800,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```

```json
{
  "name": "pcie_aspm_get_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776496,
      "name": "pcie_aspm_get_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:1079",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:clkpm_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_enabled",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776496,
      "name": "pcie_aspm_get_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pcie_link_state * pcie_aspm_get_link(struct pci_dev * pdev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
