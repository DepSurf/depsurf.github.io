# Function: <code>shpc_init</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584345120,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345120,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2676
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440400,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440400,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2669
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637737,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2042
    },
    {
      "addr": 18446744071584636672,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775433,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2038
    },
    {
      "addr": 18446744071584774368,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467074,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
    },
    {
      "addr": 18446744071585465776,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591416812,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1753
    },
    {
      "addr": 18446744071585610320,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:914",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591358939,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2035
    },
    {
      "addr": 18446744071585488768,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:914",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592387455,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2538
    },
    {
      "addr": 18446744071585955648,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:914",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594251333,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2406
    },
    {
      "addr": 18446744071587160080,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:896",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596211472,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071588370032,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2758
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:896",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596736611,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071588646016,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2735
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:896",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597645195,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071588946416,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2735
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497040072,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497040072,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2616
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275696260,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275696260,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2308
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724249,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2038
    },
    {
      "addr": 18446744071584723184,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655017,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2038
    },
    {
      "addr": 18446744071584653952,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584725593,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2038
    },
    {
      "addr": 18446744071584724528,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```

```json
{
  "name": "shpc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shpc_init",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_hpc.c:919",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833161,
      "name": "shpc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2038
    },
    {
      "addr": 18446744071584832096,
      "name": "shpc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int shpc_init(struct controller * ctrl, struct pci_dev * pdev)
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
