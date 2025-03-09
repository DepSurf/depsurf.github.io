# Function: <code>pci_dev_wait</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584200448,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4071",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_reset_bridge_secondary_bus",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pcie_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200448,
      "name": "pci_dev_wait.constprop.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584289920,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4336",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289920,
      "name": "pci_dev_wait.constprop.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4433",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484688,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584500336,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620352,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584636299,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1059",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293216,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071585319738,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1193",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448112,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071591394497,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1223",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328272,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071591336808,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1233",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_reset_bus_function",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784608,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071592363262,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1165",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_reset_bus_function",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972720,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071594225443,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int pci_dev_wait(struct pci_dev * dev, char * reset_type, int timeout)
```

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588132608,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1149",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588132608,
      "name": "pci_dev_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int pci_dev_wait(struct pci_dev * dev, char * reset_type, int timeout)
```

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588409632,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1163",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409632,
      "name": "pci_dev_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int pci_dev_wait(struct pci_dev * dev, char * reset_type, int timeout)
```

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588704864,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:1226",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588704864,
      "name": "pci_dev_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496861632,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496861632,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230141964,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230141964,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290943840,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290943840,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275563544,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275563544,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572512,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584588459,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500672,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584516587,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570512,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584586459,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_dev_wait",
      "external": false,
      "loc": "drivers/pci/pci.c:4429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pci.c:pci_af_flr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678496,
      "name": "pci_dev_wait.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071584694155,
      "name": "pci_dev_wait.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int pci_dev_wait(struct pci_dev * dev, char * reset_type, int timeout)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
