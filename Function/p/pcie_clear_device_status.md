# Function: <code>pcie_clear_device_status</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585464208,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2185",
      "file": "drivers/pci/pci.c",
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
      "addr": 18446744071585464208,
      "name": "pcie_clear_device_status",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585344336,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2215",
      "file": "drivers/pci/pci.c",
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
      "addr": 18446744071585344336,
      "name": "pcie_clear_device_status",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585803456,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2246",
      "file": "drivers/pci/pci.c",
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
      "addr": 18446744071585803456,
      "name": "pcie_clear_device_status",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991568,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2307",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/aer.c:aer_isr",
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991568,
      "name": "pcie_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588158992,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2281",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/err.c:pcie_do_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158992,
      "name": "pcie_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588434512,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2319",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434512,
      "name": "pcie_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void pcie_clear_device_status(struct pci_dev * dev)
```

```json
{
  "name": "pcie_clear_device_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588731168,
      "name": "pcie_clear_device_status",
      "external": true,
      "loc": "drivers/pci/pci.c:2416",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588731168,
      "name": "pcie_clear_device_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void pcie_clear_device_status(struct pci_dev * dev)
```
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
