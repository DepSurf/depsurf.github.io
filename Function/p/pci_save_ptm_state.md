# Function: <code>pci_save_ptm_state</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:49",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591403419,
      "name": "pci_save_ptm_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585549776,
      "name": "pci_save_ptm_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:49",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591345650,
      "name": "pci_save_ptm_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585428352,
      "name": "pci_save_ptm_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893472,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:49",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893472,
      "name": "pci_save_ptm_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587090800,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:49",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587090800,
      "name": "pci_save_ptm_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588280704,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:87",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280704,
      "name": "pci_save_ptm_state",
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
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588556528,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:87",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556528,
      "name": "pci_save_ptm_state",
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
void pci_save_ptm_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_save_ptm_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588856256,
      "name": "pci_save_ptm_state",
      "external": true,
      "loc": "drivers/pci/pcie/ptm.c:88",
      "file": "drivers/pci/pcie/ptm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_save_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588856256,
      "name": "pci_save_ptm_state",
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
void pci_save_ptm_state(struct pci_dev * dev)
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
