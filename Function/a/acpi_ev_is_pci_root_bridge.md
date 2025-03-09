# Function: <code>acpi_ev_is_pci_root_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583637919,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": false,
      "loc": "drivers/acpi/acpica/evrgnini.c:349",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
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
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961075,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": false,
      "loc": "drivers/acpi/acpica/evrgnini.c:349",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
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
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584102745,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": false,
      "loc": "drivers/acpi/acpica/evrgnini.c:350",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
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
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584169630,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": false,
      "loc": "drivers/acpi/acpica/evrgnini.c:350",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
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
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584469744,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": false,
      "loc": "drivers/acpi/acpica/evrgnini.c:350",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
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
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584693901,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": false,
      "loc": "drivers/acpi/acpica/evrgnini.c:316",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584793651,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793651,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584996434,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996434,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585132437,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585132437,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585837513,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:311",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837513,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585958664,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958664,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585835758,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835758,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586322248,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586322248,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568230,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568230,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588854480,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854480,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589143888,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143888,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589450000,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:313",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450000,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497507328,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497507328,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585037096,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037096,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584952678,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584952678,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585084021,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585084021,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ev_is_pci_root_bridge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585190181,
      "name": "acpi_ev_is_pci_root_bridge",
      "external": true,
      "loc": "drivers/acpi/acpica/evrgnini.c:312",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190181,
      "name": "acpi_ev_is_pci_root_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```
</details>
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
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u8 acpi_ev_is_pci_root_bridge(struct acpi_namespace_node * node)
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
