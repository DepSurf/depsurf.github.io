# Function: <code>dw_pcie_wr_own_conf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583715632,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/host/pcie-designware.c:143",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_msi_init",
        "drivers/pci/host/pcie-designware.c:dw_pcie_msi_init",
        "drivers/pci/host/pcie-designware.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715632,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583855520,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/host/pcie-designware.c:184",
      "file": "drivers/pci/host/pcie-designware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc",
        "drivers/pci/host/pcie-designware.c:dw_pcie_msi_init",
        "drivers/pci/host/pcie-designware.c:dw_pcie_msi_init",
        "drivers/pci/host/pcie-designware.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855520,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583905472,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/dwc/pcie-designware-host.c:36",
      "file": "drivers/pci/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905472,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584168608,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/dwc/pcie-designware-host.c:36",
      "file": "drivers/pci/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168608,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584387008,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387008,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584479024,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479024,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584677440,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677440,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584816048,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816048,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585511218,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:36",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497159712,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497159712,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230365776,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230365776,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275744594,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275744594,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584764784,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764784,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584695568,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695568,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584766208,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584766208,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```

```json
{
  "name": "dw_pcie_wr_own_conf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584873728,
      "name": "dw_pcie_wr_own_conf",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:35",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873728,
      "name": "dw_pcie_wr_own_conf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
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
int dw_pcie_wr_own_conf(struct pcie_port * pp, int where, int size, u32 val)
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
