# Function: <code>pci_read_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234400,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1015",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234400,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543424,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1032",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543424,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679744,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1151",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679744,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720128,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1177",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720128,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977728,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1219",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977728,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584177276,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1296",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172336,
      "name": "pci_read_irq.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584265306,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1296",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260416,
      "name": "pci_read_irq.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584468356,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1399",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454768,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584603707,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590096,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585267040,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1449",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585267040,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585424560,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1468",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424560,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585304768,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1511",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304768,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585761904,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1520",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761904,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586945728,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1501",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586945728,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588104064,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1507",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588104064,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379088,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1510",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379088,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void pci_read_irq(struct pci_dev * dev)
```

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588675552,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1521",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588675552,
      "name": "pci_read_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496833840,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496829296,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230114256,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230109288,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290907832,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290901744,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275539762,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275535532,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584555867,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542256,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584484027,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470416,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553867,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540256,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_read_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584661611,
      "name": "pci_read_irq",
      "external": false,
      "loc": "drivers/pci/probe.c:1401",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_setup_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584648000,
      "name": "pci_read_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void pci_read_irq(struct pci_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pci_read_irq(struct pci_dev * dev)
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
