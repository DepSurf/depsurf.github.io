# Function: <code>hv_build_pci_dev_id</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```

```json
{
  "name": "hv_build_pci_dev_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054144,
      "name": "hv_build_pci_dev_id",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:113",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054144,
      "name": "hv_build_pci_dev_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```

```json
{
  "name": "hv_build_pci_dev_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075040,
      "name": "hv_build_pci_dev_id",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:113",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075040,
      "name": "hv_build_pci_dev_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```

```json
{
  "name": "hv_build_pci_dev_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100336,
      "name": "hv_build_pci_dev_id",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:113",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100336,
      "name": "hv_build_pci_dev_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```

```json
{
  "name": "hv_build_pci_dev_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136912,
      "name": "hv_build_pci_dev_id",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:113",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136912,
      "name": "hv_build_pci_dev_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```

```json
{
  "name": "hv_build_pci_dev_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137808,
      "name": "hv_build_pci_dev_id",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:113",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137808,
      "name": "hv_build_pci_dev_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```

```json
{
  "name": "hv_build_pci_dev_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164240,
      "name": "hv_build_pci_dev_id",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:113",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164240,
      "name": "hv_build_pci_dev_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev * dev)
```
</details>
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
