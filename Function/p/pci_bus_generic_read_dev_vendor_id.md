# Function: <code>pci_bus_generic_read_dev_vendor_id</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268384,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2258",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276364,
      "name": "pci_bus_generic_read_dev_vendor_id.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071584268336,
      "name": "pci_bus_generic_read_dev_vendor_id",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584459264,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2484",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469860,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584459216,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584594576,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605214,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584594528,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585272336,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2290",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585282311,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071585272288,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585430912,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2297",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591392785,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071585430864,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311168,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2340",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591334967,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071585311120,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585767072,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2387",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592361437,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071585767024,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586952364,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2362",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594223662,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071586952320,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114080,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2374",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114080,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588389152,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2385",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389152,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588685088,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2434",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588685088,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496836352,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496836352,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230116848,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230116848,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290909712,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290909712,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275542042,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275542042,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546736,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557374,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584546688,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584474896,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485534,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584474848,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544736,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555374,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584544688,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_generic_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584652480,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2222",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_idt_bus_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663118,
      "name": "pci_bus_generic_read_dev_vendor_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584652432,
      "name": "pci_bus_generic_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
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
