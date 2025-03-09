# Function: <code>dw_pcie_prog_inbound_atu</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904800,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:247",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904800,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167712,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:249",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167712,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385792,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:246",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385792,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584477648,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:246",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477648,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:300",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676846,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584675824,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815446,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584814432,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:384",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509861,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585508816,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:392",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419680,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585640560,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:442",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361919,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585520336,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:442",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592391636,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585989952,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:446",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594256366,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587206208,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588435920,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:541",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435920,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713856,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:554",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713856,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014832,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:555",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014832,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497157776,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497157776,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230363132,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230363132,
      "name": "dw_pcie_prog_inbound_atu",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275742042,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275742042,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764182,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584763168,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694966,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584693952,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765606,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584764592,
      "name": "dw_pcie_prog_inbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
```

```json
{
  "name": "dw_pcie_prog_inbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_inbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:380",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873126,
      "name": "dw_pcie_prog_inbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584872112,
      "name": "dw_pcie_prog_inbound_atu",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, index, bar, cpu_addr, as_type</code> ➡️ <code>pci, func_no, index, bar, cpu_addr, as_type</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param added. </b>
<code>u64 pci_addr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 size</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param removed. </b>
<code>int bar</code>
</li>
<li>
<b>Param removed. </b>
<code>enum dw_pcie_as_type as_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, func_no, index, bar, cpu_addr, as_type</code> ➡️ <code>pci, index, type, cpu_addr, pci_addr, size</code>
</li>
</ul>
</details>
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
int dw_pcie_prog_inbound_atu(struct dw_pcie * pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type)
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
