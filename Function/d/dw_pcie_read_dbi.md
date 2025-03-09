# Function: <code>dw_pcie_read_dbi</code>

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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584674537,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:57",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676683,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584674448,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584812809,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815283,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584812720,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585506620,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:138",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_n_fts",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509692,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585506576,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585638940,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:139",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419370,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585638896,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585518625,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:139",
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361796,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585518576,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585988241,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:139",
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592391513,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585988192,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:139",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594256244,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587204144,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588431984,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:311",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588431984,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709824,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:324",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709824,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589010944,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:324",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "seen, unknown",
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
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589010944,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497155792,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_link_up",
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
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_link_up",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_link_up_hip06",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write",
        "drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497155792,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230361288,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_resume",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_suspend",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read",
        "drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_poll_ack",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_link_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230361288,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275740380,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275740380,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584761545,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764019,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584761456,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584692329,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694803,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584692240,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584762969,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765443,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584762880,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
```

```json
{
  "name": "dw_pcie_read_dbi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584870489,
      "name": "dw_pcie_read_dbi",
      "external": true,
      "loc": "drivers/pci/controller/dwc/pcie-designware.c:137",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability",
        "drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872963,
      "name": "dw_pcie_read_dbi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584870400,
      "name": "dw_pcie_read_dbi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
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
u32 dw_pcie_read_dbi(struct dw_pcie * pci, u32 reg, size_t size)
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
