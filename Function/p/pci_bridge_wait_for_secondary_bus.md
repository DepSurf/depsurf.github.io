# Function: <code>pci_bridge_wait_for_secondary_bus</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631584,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631584,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314624,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4736",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314624,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4809",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591395170,
      "name": "pci_bridge_wait_for_secondary_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585469504,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4858",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337485,
      "name": "pci_bridge_wait_for_secondary_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585349312,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4910",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364712,
      "name": "pci_bridge_wait_for_secondary_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585808544,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:5006",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226978,
      "name": "pci_bridge_wait_for_secondary_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586997392,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int pci_bridge_wait_for_secondary_bus(struct pci_dev * dev, char * reset_type, int timeout)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588165728,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4955",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_reset_bus_function",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165728,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int pci_bridge_wait_for_secondary_bus(struct pci_dev * dev, char * reset_type)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441568,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:5060",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_reset_bus_function",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441568,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
int pci_bridge_wait_for_secondary_bus(struct pci_dev * dev, char * reset_type)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738432,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:5170",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_reset_bus_function",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/dpc.c:dpc_reset_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738432,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496877936,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496877936,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230155028,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230155028,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290961808,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290961808,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275576174,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275576174,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583744,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583744,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511872,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511872,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581744,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581744,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_bridge_wait_for_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689456,
      "name": "pci_bridge_wait_for_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4706",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689456,
      "name": "pci_bridge_wait_for_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void pci_bridge_wait_for_secondary_bus(struct pci_dev * dev)
```
</details>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * reset_type</code>
</li>
<li>
<b>Param added. </b>
<code>int timeout</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int timeout</code>
</li>
</ul>
</details>
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
