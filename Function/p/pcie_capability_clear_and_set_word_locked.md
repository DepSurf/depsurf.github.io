# Function: <code>pcie_capability_clear_and_set_word_locked</code>

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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word_locked(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588374128,
      "name": "pcie_capability_clear_and_set_word_locked",
      "external": true,
      "loc": "drivers/pci/access.c:517",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588374128,
      "name": "pcie_capability_clear_and_set_word_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pcie_capability_clear_and_set_word_locked(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588669088,
      "name": "pcie_capability_clear_and_set_word_locked",
      "external": true,
      "loc": "drivers/pci/access.c:516",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588669088,
      "name": "pcie_capability_clear_and_set_word_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int pcie_capability_clear_and_set_word_locked(struct pci_dev * dev, int pos, u16 clear, u16 set)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
