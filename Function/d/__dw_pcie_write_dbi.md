# Function: <code>__dw_pcie_write_dbi</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie * pci, void * base, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "__dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583903648,
      "name": "__dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:80",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903648,
      "name": "__dw_pcie_write_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie * pci, void * base, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "__dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166976,
      "name": "__dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/dwc/pcie-designware.c:80",
      "file": "drivers/pci/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166976,
      "name": "__dw_pcie_write_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie * pci, void * base, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "__dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584385056,
      "name": "__dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:77",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385056,
      "name": "__dw_pcie_write_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie * pci, void * base, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "__dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584476896,
      "name": "__dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:77",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476896,
      "name": "__dw_pcie_write_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie * pci, void * base, u32 reg, size_t size, u32 val)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie * pci, void * base, u32 reg, size_t size, u32 val)
```
</details>
</li>
</ul>
