# Function: <code>pcibios_disable_device</code>

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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575968,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1558",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575968,
      "name": "pcibios_disable_device",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586757536,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1583",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757536,
      "name": "pcibios_disable_device",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586884455,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1581",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884384,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587373147,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1584",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373072,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587676955,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1639",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676880,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808251,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1812",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808176,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584488288,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1887",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113648,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584623872,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319344,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591139704,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1953",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139632,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591223944,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2089",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223872,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591173192,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2119",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173120,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592026712,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2150",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_disable_enabled_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026640,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593793744,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2210",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793648,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595736880,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2184",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595736768,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596262864,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2222",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596262752,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597145520,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2319",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597145408,
      "name": "pcibios_disable_device",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496867904,
      "name": "pcibios_disable_device",
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230145800,
      "name": "pcibios_disable_device",
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282615408,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "arch/powerpc/kernel/pci-common.c:1463",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282615408,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device",
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275567538,
      "name": "pcibios_disable_device",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584576032,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922992,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584504192,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638848,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584574032,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256400,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pcibios_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584681776,
      "name": "pcibios_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1883",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device",
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:do_pci_disable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391920,
      "name": "pcibios_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pcibios_disable_device(struct pci_dev * dev)
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
