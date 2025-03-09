# Function: <code>dw_pcie_write_dbi</code>

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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676704,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:73",
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
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676704,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584674656,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584815304,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
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
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815304,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584813264,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585507634,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:154",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_n_fts",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
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
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509672,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585506464,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585640306,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:155",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419392,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585639184,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585520071,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:155",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361818,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585518864,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585989687,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:155",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592391535,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585988480,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587205781,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:155",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594256266,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587204512,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588432528,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:327",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432528,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588710368,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:340",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710368,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589011488,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:340",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011488,
      "name": "dw_pcie_write_dbi",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497156192,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
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
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_ep_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_v3_65_scan_bus",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_v3_65_scan_bus",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_v3_65_scan_bus",
        "drivers/pci/controller/dwc/pci-keystone.c:dw_pcie_dbi_ro_wr_dis",
        "drivers/pci/controller/dwc/pci-keystone.c:dw_pcie_dbi_ro_wr_en",
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init",
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497156192,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230361628,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
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
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_resume",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_suspend",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230361628,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275740698,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu",
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
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275740698,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584764040,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
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
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764040,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584762000,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584694824,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
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
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694824,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584692784,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584765464,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
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
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765464,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584763424,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
```

```json
{
  "name": "dw_pcie_write_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584872984,
      "name": "dw_pcie_write_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:153",
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
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872984,
      "name": "dw_pcie_write_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584870944,
      "name": "dw_pcie_write_dbi",
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
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
void dw_pcie_write_dbi(struct dw_pcie * pci, u32 reg, size_t size, u32 val)
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
