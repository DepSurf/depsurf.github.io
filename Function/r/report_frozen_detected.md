# Function: <code>report_frozen_detected</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383984,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383984,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580784,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580784,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584717872,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717872,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585370800,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:82",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585370800,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585530374,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:82",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529296,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585408765,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:82",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407680,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585870845,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:82",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869728,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587085783,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:84",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587084640,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588273034,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:88",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271760,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588548659,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:88",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588547360,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588848275,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:88",
      "file": "drivers/pci/pcie/err.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588846976,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496977096,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496977096,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230241060,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230241060,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275644774,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275644774,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668352,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668352,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597504,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597504,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668032,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668032,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
```

```json
{
  "name": "report_frozen_detected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775728,
      "name": "report_frozen_detected",
      "external": false,
      "loc": "drivers/pci/pcie/err.c:78",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775728,
      "name": "report_frozen_detected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int report_frozen_detected(struct pci_dev * dev, void * data)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int report_frozen_detected(struct pci_dev * dev, void * data)
```
</details>
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
