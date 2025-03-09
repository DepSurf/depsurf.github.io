# Function: <code>pcie_do_recovery</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384016,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384016,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581428,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584580816,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718533,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584717904,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, pci_ers_result_t (*)(struct pci_dev *) reset_link)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:149",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371701,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585371152,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:172",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591399266,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585529648,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
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
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:172",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341462,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585408032,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:172",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592369294,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585870080,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:180",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler",
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594233579,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587085008,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:184",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler",
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596209715,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588272336,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:184",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler",
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596734868,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588547968,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev * dev, pci_channel_state_t state, pci_ers_result_t (*)(struct pci_dev *) reset_subordinates)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:184",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler",
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597643452,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588847584,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496977152,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496977152,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230241096,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230241096,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275644826,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275644826,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669013,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584668384,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598165,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584597536,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668693,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584668064,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
```

```json
{
  "name": "pcie_do_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_do_recovery",
      "external": true,
      "loc": "drivers/pci/pcie/err.c:186",
      "file": "drivers/pci/pcie/err.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/aer.c:aer_recover_work_func",
        "drivers/pci/pcie/dpc.c:dpc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776389,
      "name": "pcie_do_recovery.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584775760,
      "name": "pcie_do_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pci_ers_result_t (*)(struct pci_dev *) reset_link</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 service</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>pci_ers_result_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pci_ers_result_t (*)(struct pci_dev *) reset_subordinates</code>
</li>
<li>
<b>Param removed. </b>
<code>pci_ers_result_t (*)(struct pci_dev *) reset_link</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum pci_channel_state state</code> ➡️ <code>pci_channel_state_t state</code>
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
void pcie_do_recovery(struct pci_dev * dev, enum pci_channel_state state, u32 service)
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
