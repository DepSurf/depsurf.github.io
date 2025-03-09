# Function: <code>pci_bus_distribute_available_resources</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584048544,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1881",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584048544,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1753
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584248480,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1876",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248480,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338240,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1878",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338240,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532336,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1842",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532336,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667472,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667472,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585352400,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1886",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585352400,
      "name": "pci_bus_distribute_available_resources.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1862
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585504128,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1887",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504128,
      "name": "pci_bus_distribute_available_resources.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1882
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
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585382352,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1887",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382352,
      "name": "pci_bus_distribute_available_resources.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1870
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
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585843744,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1887",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843744,
      "name": "pci_bus_distribute_available_resources.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1880
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
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587036832,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1887",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036832,
      "name": "pci_bus_distribute_available_resources.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1834
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, struct resource io, struct resource mmio, struct resource mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216528,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1832",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216528,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2071
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, struct resource io, struct resource mmio, struct resource mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492288,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1823",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492288,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1806
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, struct resource io, struct resource mmio, struct resource mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588790608,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1833",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588790608,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1843
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496917072,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496917072,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230192964,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230192964,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291014160,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291014160,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275603356,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275603356,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617936,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617936,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584547760,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547760,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617632,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617632,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```

```json
{
  "name": "pci_bus_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584725328,
      "name": "pci_bus_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1848",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584725328,
      "name": "pci_bus_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus * bus, struct list_head * add_list, struct resource io, struct resource mmio, struct resource mmio_pref)
```
</details>
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
