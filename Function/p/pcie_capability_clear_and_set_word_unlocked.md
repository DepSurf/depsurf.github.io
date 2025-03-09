# Function: <code>pcie_capability_clear_and_set_word_unlocked</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pcie_capability_clear_and_set_word_unlocked(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588374204,
      "name": "pcie_capability_clear_and_set_word_unlocked",
      "external": true,
      "loc": "drivers/pci/access.c:500",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word_locked"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373968,
      "name": "pcie_capability_clear_and_set_word_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pcie_capability_clear_and_set_word_unlocked(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588669164,
      "name": "pcie_capability_clear_and_set_word_unlocked",
      "external": true,
      "loc": "drivers/pci/access.c:500",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word_locked"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668928,
      "name": "pcie_capability_clear_and_set_word_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int pcie_capability_clear_and_set_word_unlocked(struct pci_dev * dev, int pos, u16 clear, u16 set)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
