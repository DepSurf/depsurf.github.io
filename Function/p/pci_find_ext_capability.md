# Function: <code>pci_find_ext_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583259808,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:343",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259808,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569971,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:364",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:aer_isr",
        "drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/aer/aerdrv.c:aer_irq",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569888,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583706371,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:364",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_aer_init",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706288,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583756268,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:366",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_acs_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_aer_init",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746928,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005829,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:367",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_aer_init",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005744,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584201205,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:379",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_std_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200704,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584290437,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290176,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584480853,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/probe.c:program_hpx_type3",
        "drivers/pci/probe.c:program_hpx_type3",
        "drivers/pci/probe.c:program_hpp_type2",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480752,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584480784,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584616325,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616224,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584616256,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585294485,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:577",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_disable_acs_redir",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_get_dsn",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_disable_acs_redir",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292064,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585294064,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448981,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:585",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_get_dsn",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_save_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448736,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585329141,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:585",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_get_dsn",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_save_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328896,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585786149,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:595",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_get_dsn",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_save_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785840,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586964461,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:612",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_find_dvsec_capability",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_slot",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aspm.c:pci_restore_aspm_l1ss_state",
        "drivers/pci/pcie/aspm.c:pci_save_aspm_l1ss_state",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pcie/ptm.c:pci_restore_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_save_ptm_state",
        "drivers/pci/pcie/ptm.c:pci_disable_ptm",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963808,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588128525,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:596",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_find_dvsec_capability",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_slot",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:dpc_log_size",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588127808,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588403789,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:611",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_find_dvsec_capability",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_slot",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:dpc_log_size",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403072,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u16 pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588699773,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:611",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_init",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_restore_rebar_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_find_dvsec_capability",
        "drivers/pci/pci.c:pci_get_dsn"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_slot",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_enable",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/rcec.c:pci_rcec_init",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:pci_dpc_init",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:dpc_log_size",
        "drivers/pci/ats.c:pci_pasid_init",
        "drivers/pci/ats.c:pci_pri_init",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588699056,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496856744,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496856560,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336496856616,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230137600,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230137460,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3230137496,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290937648,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290937536,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 13835058055290937568,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275559098,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275558948,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446743936275559000,
      "name": "pci_find_ext_capability",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584568485,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568384,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584568416,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584496645,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496544,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584496576,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584566485,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566384,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584566416,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_find_ext_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_ext_capability",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584674469,
      "name": "pci_find_ext_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:545",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_rebar_find_pos",
        "drivers/pci/pci.c:pci_acs_flags_enabled",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_enable_acs",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/vc.c:pci_allocate_vc_save_buffers",
        "drivers/pci/vc.c:pci_restore_vc_state",
        "drivers/pci/vc.c:pci_save_vc_state",
        "drivers/pci/vc.c:pci_vc_do_save_buffer",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:pci_idt_bus_quirk",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_init",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/pcie/ptm.c:pci_enable_ptm",
        "drivers/pci/pcie/ptm.c:pci_ptm_init",
        "drivers/pci/ats.c:pci_max_pasids",
        "drivers/pci/ats.c:pci_prg_resp_pasid_required",
        "drivers/pci/ats.c:pci_pasid_features",
        "drivers/pci/ats.c:pci_disable_pasid",
        "drivers/pci/ats.c:pci_enable_pasid",
        "drivers/pci/ats.c:pci_reset_pri",
        "drivers/pci/ats.c:pci_restore_pri_state",
        "drivers/pci/ats.c:pci_disable_pri",
        "drivers/pci/ats.c:pci_enable_pri",
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/pci/iov.c:pci_iov_init",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584674368,
      "name": "pci_find_ext_capability.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584674400,
      "name": "pci_find_ext_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u16</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
