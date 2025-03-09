# Function: <code>pcie_get_speed_cap</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584214416,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5266",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214416,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288576,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5554",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288576,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584483456,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5648",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483456,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618912,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618912,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288768,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5808",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288768,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585444720,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5882",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444720,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324880,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5931",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324880,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778128,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:6121",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778128,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965968,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:6217",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965968,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588130432,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:6164",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588130432,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588405728,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:6286",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588405728,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588700768,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:6430",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700768,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496859944,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496859944,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230140472,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230140472,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290942240,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290942240,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275562242,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275562242,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584571072,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571072,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584499232,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499232,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584569072,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569072,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```

```json
{
  "name": "pcie_get_speed_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584677056,
      "name": "pcie_get_speed_cap",
      "external": true,
      "loc": "drivers/pci/pci.c:5778",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677056,
      "name": "pcie_get_speed_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev * dev)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
