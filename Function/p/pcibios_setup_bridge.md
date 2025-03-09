# Function: <code>pcibios_setup_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583608768,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:698",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583608768,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745968,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:699",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745968,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583787824,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:690",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787824,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050304,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:690",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050304,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249856,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:685",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249856,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339600,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:685",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339600,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533808,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533808,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668944,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668944,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585356096,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:683",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356096,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507840,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:684",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507840,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585386304,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:684",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386304,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585847712,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:684",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847712,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040800,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:684",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040800,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 15
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221392,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:684",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_setup_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221392,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 15
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588496880,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:681",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_setup_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496880,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 15
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588795152,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:690",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_setup_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795152,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 15
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496918512,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496918512,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230194308,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230194308,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282610992,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "arch/powerpc/kernel/pci-common.c:209",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282610992,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275604436,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275604436,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619408,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619408,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549232,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549232,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619104,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619104,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```

```json
{
  "name": "pcibios_setup_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584726800,
      "name": "pcibios_setup_bridge",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:682",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726800,
      "name": "pcibios_setup_bridge",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void pcibios_setup_bridge(struct pci_bus * bus, long unsigned int type)
```
</details>
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
