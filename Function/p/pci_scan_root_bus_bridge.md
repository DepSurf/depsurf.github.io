# Function: <code>pci_scan_root_bus_bridge</code>

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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734208,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:2497",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734208,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583992864,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:2724",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583992864,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186976,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:2941",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186976,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275680,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3067",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275680,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3291",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470845,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584466000,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606129,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584601376,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3077",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585283272,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071585278736,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3084",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591393760,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071585437440,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3128",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591336071,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071585317568,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3170",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592362541,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071585773456,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3141",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594224708,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586959216,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588122400,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3151",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588122400,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588397664,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3165",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588397664,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588693648,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3214",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693648,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496843984,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496843984,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230124600,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/bios32.c:pci_common_init_dev",
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230124600,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290920464,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290920464,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275548670,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275548670,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558289,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584553536,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486449,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584481696,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556289,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584551536,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
```

```json
{
  "name": "pci_scan_root_bus_bridge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_scan_root_bus_bridge",
      "external": true,
      "loc": "drivers/pci/probe.c:3025",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_host_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664033,
      "name": "pci_scan_root_bus_bridge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584659280,
      "name": "pci_scan_root_bus_bridge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pci_scan_root_bus_bridge(struct pci_host_bridge * bridge)
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
