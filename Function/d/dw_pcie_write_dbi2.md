# Function: <code>dw_pcie_write_dbi2</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:103",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676745,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584674896,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815345,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584813504,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:184",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509757,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585507824,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:170",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419660,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585640384,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:170",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361899,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585520160,
      "name": "dw_pcie_write_dbi2",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:170",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592391616,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585989776,
      "name": "dw_pcie_write_dbi2",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:170",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594256346,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587205904,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588435552,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:342",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435552,
      "name": "dw_pcie_write_dbi2",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713488,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:355",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713488,
      "name": "dw_pcie_write_dbi2",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589012880,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:355",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012880,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497156720,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_ep_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497156720,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230362108,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230362108,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275741152,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275741152,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764081,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584762240,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694865,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584693024,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765505,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584763664,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_write_dbi2",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:183",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873025,
      "name": "dw_pcie_write_dbi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584871184,
      "name": "dw_pcie_write_dbi2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void dw_pcie_write_dbi2(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
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
