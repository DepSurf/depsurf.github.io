# Function: <code>dw_pcie_ep_raise_msix_irq</code>

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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584482464,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:426",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482464,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:441",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680596,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584680080,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819140,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584818624,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:430",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514214,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585513696,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585650256,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:561",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650256,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585531088,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:559",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531088,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586001136,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:559",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001136,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587218528,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:562",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587218528,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451088,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:564",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451088,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588730192,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:564",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588730192,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589033072,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:522",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589033072,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497168040,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497168040,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230372188,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230372188,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275750676,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275750676,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767876,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584767360,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698660,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584698144,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769300,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584768784,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msix_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msix_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:408",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584876820,
      "name": "dw_pcie_ep_raise_msix_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584876304,
      "name": "dw_pcie_ep_raise_msix_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep * ep, u8 func_no, u16 interrupt_num)
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
