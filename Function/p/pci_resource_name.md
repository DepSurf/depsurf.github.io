# Function: <code>pci_resource_name</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * pci_resource_name(struct pci_dev * dev, unsigned int i)
```

```json
{
  "name": "pci_resource_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588744040,
      "name": "pci_resource_name",
      "external": true,
      "loc": "drivers/pci/pci.c:860",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_ea_read"
      ],
      "caller_func": [
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/setup-res.c:pci_enable_resources",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pbus_size_mem",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:reassign_resources_sorted",
        "drivers/pci/quirks.c:quirk_io",
        "drivers/pci/quirks.c:quirk_extend_bar_to_page",
        "drivers/pci/iov.c:sriov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723168,
      "name": "pci_resource_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
const char * pci_resource_name(struct pci_dev * dev, unsigned int i)
```
</details>
</li>
</ul>
