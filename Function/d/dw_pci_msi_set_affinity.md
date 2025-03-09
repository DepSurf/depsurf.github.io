# Function: <code>dw_pci_msi_set_affinity</code>

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
int dw_pci_msi_set_affinity(struct irq_data * irq_data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386688,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:149",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386688,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int dw_pci_msi_set_affinity(struct irq_data * irq_data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478560,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:146",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478560,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:140",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:142",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585641632,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:119",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585641632,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522480,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:119",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522480,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585992192,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:118",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585992192,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587208576,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:118",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587208576,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588438496,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:117",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438496,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588717504,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:117",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717504,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589018496,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:119",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589018496,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497159280,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497159280,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230364616,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230364616,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275743456,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275743456,
      "name": "dw_pci_msi_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dw_pci_msi_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dw_pci_msi_set_affinity",
      "external": false,
      "loc": "drivers/pci/controller/dwc/pcie-designware-host.c:141",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int dw_pci_msi_set_affinity(struct irq_data * irq_data, const struct cpumask * mask, bool force)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data * irq_data, const struct cpumask * mask, bool force)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data * d, const struct cpumask * mask, bool force)
```
</details>
</li>
</ul>
