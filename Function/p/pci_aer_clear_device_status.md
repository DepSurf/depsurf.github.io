# Function: <code>pci_aer_clear_device_status</code>

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
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395968,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395968,
      "name": "pci_aer_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592208,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592208,
      "name": "pci_aer_clear_device_status",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584730032,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730032,
      "name": "pci_aer_clear_device_status",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585384096,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:244",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384096,
      "name": "pci_aer_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496990848,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496990848,
      "name": "pci_aer_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230252732,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230252732,
      "name": "pci_aer_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275656054,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275656054,
      "name": "pci_aer_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679712,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679712,
      "name": "pci_aer_clear_device_status",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584609664,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584609664,
      "name": "pci_aer_clear_device_status",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680192,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680192,
      "name": "pci_aer_clear_device_status",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pci_aer_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787888,
      "name": "pci_aer_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pcie/aer.c:369",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_process_err_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787888,
      "name": "pci_aer_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void pci_aer_clear_device_status(struct pci_dev * dev)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void pci_aer_clear_device_status(struct pci_dev * dev)
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
void pci_aer_clear_device_status(struct pci_dev * dev)
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
