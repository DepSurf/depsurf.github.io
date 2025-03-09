# Function: <code>pci_create_root_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243952,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2091",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243952,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553248,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2129",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/pci/probe.c:pci_scan_root_bus_msi",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553248,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583693701,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2310",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_scan_bus"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691168,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731424,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2405",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731424,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583989520,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2632",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989520,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183712,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2816",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183712,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584272416,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2942",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272416,
      "name": "pci_create_root_bus",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462784,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3168",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462784,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584598128,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598128,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275296,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2954",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275296,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434000,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2961",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434000,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314224,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3005",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314224,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585770112,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3047",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585770112,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586955792,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3018",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955792,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588118656,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3028",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588118656,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393808,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3042",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393808,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588689792,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:3091",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689792,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496840624,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496840624,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230121076,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230121076,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290916048,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_scan_phb",
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290916048,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275545828,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275545828,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584550288,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550288,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478448,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478448,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584548288,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548288,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct pci_bus * pci_create_root_bus(struct device * parent, int bus, struct pci_ops * ops, void * sysdata, struct list_head * resources)
```

```json
{
  "name": "pci_create_root_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584656032,
      "name": "pci_create_root_bus",
      "external": true,
      "loc": "drivers/pci/probe.c:2902",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/pci/probe.c:pci_scan_root_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656032,
      "name": "pci_create_root_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
