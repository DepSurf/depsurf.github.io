# Function: <code>pci_set_low_power_state</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_set_low_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_low_power_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_set_low_power_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1357",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979392,
      "name": "pci_set_low_power_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071594225906,
      "name": "pci_set_low_power_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_set_low_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_low_power_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148080,
      "name": "pci_set_low_power_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1338",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148080,
      "name": "pci_set_low_power_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int pci_set_low_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_low_power_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423632,
      "name": "pci_set_low_power_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1376",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423632,
      "name": "pci_set_low_power_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int pci_set_low_power_state(struct pci_dev * dev, pci_power_t state, bool locked)
```

```json
{
  "name": "pci_set_low_power_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588719920,
      "name": "pci_set_low_power_state",
      "external": false,
      "loc": "drivers/pci/pci.c:1458",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/pci.c:__pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588719920,
      "name": "pci_set_low_power_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int pci_set_low_power_state(struct pci_dev * dev, pci_power_t state)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool locked</code>
</li>
</ul>
</details>
</li>
</ul>
