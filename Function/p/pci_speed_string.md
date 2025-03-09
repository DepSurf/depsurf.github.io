# Function: <code>pci_speed_string</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585265200,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:687",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585265200,
      "name": "pci_speed_string",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422704,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:693",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422704,
      "name": "pci_speed_string",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303216,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:694",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303216,
      "name": "pci_speed_string",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585760304,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:696",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585760304,
      "name": "pci_speed_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944832,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:695",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944832,
      "name": "pci_speed_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588103056,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:695",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588103056,
      "name": "pci_speed_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588378080,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:696",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378080,
      "name": "pci_speed_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * pci_speed_string(enum pci_bus_speed speed)
```

```json
{
  "name": "pci_speed_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588673264,
      "name": "pci_speed_string",
      "external": true,
      "loc": "drivers/pci/probe.c:707",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci.c:__pcie_print_link_status",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/slot.c:cur_speed_read_file",
        "drivers/pci/slot.c:max_speed_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588673264,
      "name": "pci_speed_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const char * pci_speed_string(enum pci_bus_speed speed)
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
