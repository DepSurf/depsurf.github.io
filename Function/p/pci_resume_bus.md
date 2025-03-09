# Function: <code>pci_resume_bus</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585461165,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1187",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462784,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585341052,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585342896,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585798044,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1227",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799296,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586985200,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1159",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985200,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588152064,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588152064,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427616,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1157",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427616,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void pci_resume_bus(struct pci_bus * bus)
```

```json
{
  "name": "pci_resume_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588724096,
      "name": "pci_resume_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:1220",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724096,
      "name": "pci_resume_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void pci_resume_bus(struct pci_bus * bus)
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
