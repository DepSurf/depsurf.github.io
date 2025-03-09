# Function: <code>pci_configure_extended_tags</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583721133,
      "name": "pci_configure_extended_tags",
      "external": false,
      "loc": "drivers/pci/probe.c:1748",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984208,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1790",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984208,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584178096,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1933",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178096,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584266128,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1982",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266128,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584458136,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2192",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469658,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584458048,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584593448,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605012,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584593360,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585269718,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2005",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585267552,
      "name": "pci_configure_extended_tags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071585280290,
      "name": "pci_configure_extended_tags.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585272176,
      "name": "pci_configure_extended_tags",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585426934,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2008",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585425072,
      "name": "pci_configure_extended_tags.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071591392008,
      "name": "pci_configure_extended_tags.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585430752,
      "name": "pci_configure_extended_tags",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585310550,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2051",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591334877,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585310464,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585766454,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2086",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592361347,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585766368,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2059",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594223574,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586951632,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588113264,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2065",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113264,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388336,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2075",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388336,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588684272,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:2124",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588684272,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496835048,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496835048,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230115500,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230115500,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290909344,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290909344,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275540938,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275540938,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584545608,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557172,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584545520,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473768,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485332,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584473680,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584543608,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555172,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584543520,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
```

```json
{
  "name": "pci_configure_extended_tags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584651352,
      "name": "pci_configure_extended_tags",
      "external": true,
      "loc": "drivers/pci/probe.c:1937",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662916,
      "name": "pci_configure_extended_tags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584651264,
      "name": "pci_configure_extended_tags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pci_configure_extended_tags(struct pci_dev * dev, void * ign)
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
