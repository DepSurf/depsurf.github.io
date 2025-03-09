# Function: <code>dw_pcie_ep_raise_msi_irq</code>

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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389888,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:290",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389888,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584482128,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:383",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482128,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:395",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680566,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584679760,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819110,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584818304,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:384",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514184,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585513376,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649728,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:491",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649728,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530544,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:489",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530544,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000592,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:489",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000592,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587214880,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:491",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587214880,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447120,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:493",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447120,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726208,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:493",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726208,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589030128,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:454",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589030128,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497167696,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497167696,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230371880,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230371880,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275750340,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275750340,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767846,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584767040,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698630,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584697824,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769270,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584768464,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
```

```json
{
  "name": "dw_pcie_ep_raise_msi_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_ep_raise_msi_irq",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware-ep.c:362",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584876790,
      "name": "dw_pcie_ep_raise_msi_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584875984,
      "name": "dw_pcie_ep_raise_msi_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep * ep, u8 func_no, u8 interrupt_num)
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
