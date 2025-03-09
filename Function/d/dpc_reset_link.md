# Function: <code>dpc_reset_link</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584307824,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:75",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307824,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584403696,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:119",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403696,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598864,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584600279,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736688,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584738103,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:92",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391866,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585390736,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:92",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402190,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585547824,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:144",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591344978,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585426720,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:144",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592372016,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585891792,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:144",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594233854,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587088256,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276416,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:144",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276416,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588551888,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:144",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588551888,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588851552,
      "name": "dpc_reset_link",
      "external": true,
      "loc": "drivers/pci/pcie/dpc.c:148",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851552,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496999008,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496999008,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230258536,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230258536,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275662480,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275662480,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584685504,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584686919,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616272,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584617687,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686848,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584688263,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_reset_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpc_reset_link",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584794496,
      "name": "dpc_reset_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071584795911,
      "name": "dpc_reset_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev * pdev)
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
