# Function: <code>dpc_process_rp_pio_error</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584106538,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/pcie-dpc.c:238",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pcie-dpc.c:dpc_irq"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584306715,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:124",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/dpc.c:dpc_irq"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584402064,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:149",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402064,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599288,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599288,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737112,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737112,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585391896,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:120",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391896,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591402272,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:123",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402272,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591344409,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:187",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591344409,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592371376,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:187",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592371376,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594233945,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:187",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594233945,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276832,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:187",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276832,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588552304,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:186",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552304,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
void dpc_process_rp_pio_error(struct pci_dev * pdev)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588851968,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:190",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_process_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851968,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496999572,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496999572,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230260148,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230260148,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275662950,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275662950,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584685928,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584685928,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584616696,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616696,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687272,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687272,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
```

```json
{
  "name": "dpc_process_rp_pio_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794920,
      "name": "dpc_process_rp_pio_error",
      "external": false,
      "loc": "drivers/pci/pcie/dpc.c:150",
      "file": "drivers/pci/pcie/dpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584794920,
      "name": "dpc_process_rp_pio_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev * pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dpc_dev * dpc</code>
</li>
</ul>
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
void dpc_process_rp_pio_error(struct dpc_dev * dpc)
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
