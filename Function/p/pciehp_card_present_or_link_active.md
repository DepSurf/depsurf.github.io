# Function: <code>pciehp_card_present_or_link_active</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584424096,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:392",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424096,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620528,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:394",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620528,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758416,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758416,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585449584,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:461",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585449584,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585597888,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:464",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597888,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476224,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:464",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476224,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942512,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:464",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942512,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587145888,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:466",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145888,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588350608,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:466",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350608,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626864,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:460",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626864,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588927040,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:461",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927040,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497022392,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497022392,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275680942,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275680942,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707232,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707232,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638000,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638000,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584708576,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708576,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present_or_link_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584816160,
      "name": "pciehp_card_present_or_link_active",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816160,
      "name": "pciehp_card_present_or_link_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool pciehp_card_present_or_link_active(struct controller * ctrl)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
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
int pciehp_card_present_or_link_active(struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pciehp_card_present_or_link_active(struct controller * ctrl)
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
