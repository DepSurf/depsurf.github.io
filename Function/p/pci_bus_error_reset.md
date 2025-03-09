# Function: <code>pci_bus_error_reset</code>

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
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304400,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5223",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304400,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498128,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5321",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498128,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584634032,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634032,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316784,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5481",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316784,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585471744,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5549",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471744,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585351664,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5598",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351664,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810656,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5788",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810656,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586999616,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5884",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586999616,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588168160,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5821",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168160,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588444400,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5943",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444400,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588741264,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:6053",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741264,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496880600,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496880600,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230157684,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230157684,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290965200,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290965200,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275578524,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275578524,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584586192,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586192,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584514320,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584514320,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584584192,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584192,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev * bridge)
```

```json
{
  "name": "pci_bus_error_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584691856,
      "name": "pci_bus_error_reset",
      "external": true,
      "loc": "drivers/pci/pci.c:5451",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584691856,
      "name": "pci_bus_error_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int pci_bus_error_reset(struct pci_dev * bridge)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
