# Function: <code>pcie_report_downtraining</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584268936,
      "name": "pcie_report_downtraining",
      "external": false,
      "loc": "drivers/pci/probe.c:2325",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584459520,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2551",
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
      "addr": 18446744071584459520,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584594832,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446744071584594832,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585272592,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2357",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_init_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272592,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585431168,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2364",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_init_capabilities"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431168,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311424,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2408",
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
      "addr": 18446744071585311424,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585767328,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2452",
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
      "addr": 18446744071585767328,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586952640,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2427",
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
      "addr": 18446744071586952640,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114608,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2439",
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
      "addr": 18446744071588114608,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588389680,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2450",
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
      "addr": 18446744071588389680,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588685616,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2499",
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
      "addr": 18446744071588685616,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496836928,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446603336496836928,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230117348,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 3230117348,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290910480,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 13835058055290910480,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275542476,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446743936275542476,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546992,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446744071584546992,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584475152,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446744071584475152,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544992,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446744071584544992,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pcie_report_downtraining(struct pci_dev * dev)
```

```json
{
  "name": "pcie_report_downtraining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584652736,
      "name": "pcie_report_downtraining",
      "external": true,
      "loc": "drivers/pci/probe.c:2289",
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
      "addr": 18446744071584652736,
      "name": "pcie_report_downtraining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void pcie_report_downtraining(struct pci_dev * dev)
```
</details>
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
