# Function: <code>pcie_walk_rcec</code>

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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585531040,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531040,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585409408,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409408,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871488,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871488,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587064528,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064528,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588249760,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588249760,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588525312,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588525312,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pcie_walk_rcec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588823952,
      "name": "pcie_walk_rcec",
      "external": true,
      "loc": "drivers/pci/pcie/rcec.c:134",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:aer_process_err_devices",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823952,
      "name": "pcie_walk_rcec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pcie_walk_rcec(struct pci_dev * rcec, int (*)(struct pci_dev *, void *) cb, void * userdata)
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
