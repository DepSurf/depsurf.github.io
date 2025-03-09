# Function: <code>pci_claim_bridge_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298000,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:708",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298000,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583608832,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:712",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583608832,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583746032,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:713",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746032,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583787888,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:704",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787888,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584050368,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:704",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050368,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584249920,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:699",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249920,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584339664,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:699",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339664,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584533872,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533872,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584669008,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669008,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585356160,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:697",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356160,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585507904,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:698",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507904,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386368,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:698",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386368,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585847776,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:698",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847776,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040880,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:698",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040880,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221568,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:698",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221568,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588497056,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:695",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588497056,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588795328,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:704",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795328,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496918600,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496918600,
      "name": "pci_claim_bridge_resource",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230194380,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230194380,
      "name": "pci_claim_bridge_resource",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291015744,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_claim_one_bus",
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources",
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291015744,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275604528,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275604528,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584619472,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619472,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584549296,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549296,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584619168,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619168,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pci_claim_bridge_resource(struct pci_dev * bridge, int i)
```

```json
{
  "name": "pci_claim_bridge_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584726864,
      "name": "pci_claim_bridge_resource",
      "external": true,
      "loc": "drivers/pci/setup-bus.c:696",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_allocate_resources",
        "arch/x86/pci/i386.c:pcibios_allocate_bus_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726864,
      "name": "pci_claim_bridge_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
