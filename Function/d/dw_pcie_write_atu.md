# Function: <code>dw_pcie_write_atu</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676786,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:132",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676786,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584675136,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584815386,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815386,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584813744,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585508095,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:213",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509799,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585508048,
      "name": "dw_pcie_write_atu",
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497157040,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497157040,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230362408,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230362408,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275741402,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275741402,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584764122,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764122,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584762480,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584694906,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694906,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584693264,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584765546,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765546,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584763904,
      "name": "dw_pcie_write_atu",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_atu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584873066,
      "name": "dw_pcie_write_atu",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:212",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873066,
      "name": "dw_pcie_write_atu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584871424,
      "name": "dw_pcie_write_atu",
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
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```
</details>
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
void dw_pcie_write_atu(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
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
