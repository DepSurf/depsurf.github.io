# Function: <code>dw_pcie_prog_outbound_atu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583717720,
      "name": "dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/host/pcie-designware.c:152",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct pcie_port * pp, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854512,
      "name": "dw_pcie_prog_outbound_atu",
      "external": false,
      "loc": "drivers/pci/host/pcie-designware.c:193",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854512,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1001
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904064,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:145",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904064,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167072,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:146",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167072,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385152,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:143",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385152,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476992,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:143",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476992,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:197",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676806,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584675248,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815406,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584813856,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:281",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509840,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585508448,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640496,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:315",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640496,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520272,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:365",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520272,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989888,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:365",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989888,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587206096,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:369",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206096,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588435792,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:515",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435792,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713728,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:528",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713728,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014704,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:529",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014704,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497157176,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497157176,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230362532,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230362532,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275741518,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275741518,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764142,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584762592,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694926,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584693376,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765566,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584764016,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```

```json
{
  "name": "dw_pcie_prog_outbound_atu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_prog_outbound_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:277",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873086,
      "name": "dw_pcie_prog_outbound_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584871536,
      "name": "dw_pcie_prog_outbound_atu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void dw_pcie_prog_outbound_atu(struct pcie_port * pp, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dw_pcie * pci</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pcie_port * pp</code>
</li>
</ul>
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
<b>Param type changed. </b>
<code>u32 size</code> ➡️ <code>u64 size</code>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
void dw_pcie_prog_outbound_atu(struct dw_pcie * pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size)
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
