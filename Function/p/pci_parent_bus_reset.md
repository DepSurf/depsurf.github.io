# Function: <code>pci_parent_bus_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583270089,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:3555",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583580541,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:3876",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583717597,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:3914",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757824,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4032",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757824,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017184,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4069",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017184,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213120,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4318",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213120,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302688,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4611",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302688,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584496400,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4708",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496400,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632304,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632304,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585315408,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4868",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315408,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470288,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4942",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470288,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350080,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4991",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350080,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585809771,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5043",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586998695,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5139",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588167079,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5076",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588443271,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5198",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588740135,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:5308",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reset_bus_function"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496878752,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496878752,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230155808,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230155808,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290962816,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290962816,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275576934,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275576934,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584584464,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584464,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512592,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512592,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582464,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582464,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```

```json
{
  "name": "pci_parent_bus_reset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690176,
      "name": "pci_parent_bus_reset",
      "external": false,
      "loc": "drivers/pci/pci.c:4838",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690176,
      "name": "pci_parent_bus_reset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int pci_parent_bus_reset(struct pci_dev * dev, int probe)
```
</details>
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
