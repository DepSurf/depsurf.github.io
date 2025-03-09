# Function: <code>xhci_find_next_ext_cap</code>

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
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585732767,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:106",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585872226,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:106",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585921359,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:106",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586061074,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:106",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586005710,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:106",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586143499,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:106",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586449854,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:94",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586588299,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:94",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586660432,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:94",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586668986,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:94",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586714936,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586866094,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586868281,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586924208,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586934058,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872668,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587021344,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587023593,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587081216,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587091226,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098976,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098976,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587131153,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587271724,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587285305,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587345024,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356093,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587363824,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587363824,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587331537,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587472113,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587486009,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587546800,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587557773,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587565664,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587565664,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588187141,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588335649,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588348676,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588406580,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588420842,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588426578,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_reset_debug_port"
      ],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/usb/early/xhci-dbc.c:xdbc_bios_handoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425680,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588224725,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588366961,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588379700,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436900,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451130,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588457090,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_reset_debug_port"
      ],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_bios_handoff",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456176,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588107973,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588249502,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588262084,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319892,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334010,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591512841,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591512841,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588741936,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588898240,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912948,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977428,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588991914,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592616137,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592616137,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590159123,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590327469,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590342468,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590415186,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590427120,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594499210,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594499210,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591774387,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591954903,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591971284,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592052626,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592065424,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628113616,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592197655,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592376047,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592392340,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592475426,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592488336,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619880144,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:98",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592938375,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:125",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593118543,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:125",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593135284,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:125",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593219522,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:125",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593232624,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:125",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622189824,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:125",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500448772,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500622308,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500623780,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500690324,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500706004,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232903832,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233069384,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 3233083076,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233147780,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233161416,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293804324,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294019680,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294039524,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294123404,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294138716,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277338314,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277477562,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277490650,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277547566,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277557416,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587037617,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587178145,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587192041,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587254109,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586898145,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586936897,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586950793,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011584,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587022557,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587286097,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587426673,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587440569,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587501360,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512333,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```

```json
{
  "name": "xhci_find_next_ext_cap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587392865,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587533537,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587547545,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587609232,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587620205,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587628128,
      "name": "xhci_find_next_ext_cap",
      "external": false,
      "loc": "drivers/usb/host/xhci-ext-caps.h:97",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587628128,
      "name": "xhci_find_next_ext_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int xhci_find_next_ext_cap(void * base, u32 start, int id)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
