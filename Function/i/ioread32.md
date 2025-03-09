# Function: <code>ioread32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049520,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:86",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_update_timeouts",
        "drivers/char/tpm/tpm_tis.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049520,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343584,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:86",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343584,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468960,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:86",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468960,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491200,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:86",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491200,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672240,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:87",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672240,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890016,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:87",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890016,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974256,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:87",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974256,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156368,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156368,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290112,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290112,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700480,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700480,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584813776,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813776,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858336,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858336,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279792,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279792,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131184,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131184,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587122048,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:97",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32le",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122048,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587384256,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:97",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32le",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384256,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
unsigned int ioread32(const void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718608,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:97",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32le",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718608,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ioread32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496409236,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496447452,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/bus/brcmstb_gisb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/brcmstb_gisb.c:gisb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496643136,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496801412,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/gpio/gpio-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xgene.c:xgene_gpio_suspend",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_get_direction",
        "drivers/gpio/gpio-xgene.c:__xgene_gpio_set",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496958300,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497182100,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pci/controller/dwc/pci-layerscape.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init",
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497792248,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497792880,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498118156,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/soc/fsl/guts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/guts.c:fsl_guts_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511197328,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511198148,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498179032,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498181488,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498189216,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498610412,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498816988,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498820872,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499692840,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500041600,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/net/ethernet/freescale/xgmac_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500099580,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500372988,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501520484,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_rx_callback",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501529468,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501574868,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501582612,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501736416,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/memory/fsl_ifc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq",
        "drivers/memory/fsl_ifc.c:check_nand_stat"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ioread32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243350988,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "arch/arm/mach-shmobile/setup-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243352404,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 3229740296,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/irqchip/irq-renesas-intc-irqpin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3229744764,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3229761272,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/bus/brcmstb_gisb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_suspend",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:gisb_arb_get_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 3229929112,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955376,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3229964760,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pinctrl/sh-pfc/pfc-r8a7778.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_get_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3229965020,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pinctrl/sh-pfc/pfc-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_is_enabled",
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230224832,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 3230325364,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pci/controller/pci-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3230617036,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243597852,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243772904,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clk/renesas/clk-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230875696,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/soc/fsl/guts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/guts.c:fsl_guts_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243838148,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 3243839064,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3230942008,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230945704,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952932,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 3231231708,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231428384,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3231456388,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/iommu/ipmmu-vmsa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_irq",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_irq",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_tlb_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 3232137352,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3232560184,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/net/ethernet/freescale/xgmac_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_done",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3232830184,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234034980,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_rx_callback",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response"
      ],
      "caller_func": []
    },
    {
      "addr": 3234042832,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234087096,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3234094524,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 3234097820,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clocksource/em_sti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/em_sti.c:em_sti_count",
        "drivers/clocksource/em_sti.c:em_sti_count"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290445984,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290445984,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ioread32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275630000,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275927536,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275958924,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275962278,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969456,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276197748,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276314512,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276860484,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277005202,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/spi/spi-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277259620,
      "name": "ioread32",
      "external": false,
      "loc": "include/asm-generic/io.h:702",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258848,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258848,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194048,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194048,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242608,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242608,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int ioread32(void * addr)
```

```json
{
  "name": "ioread32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347440,
      "name": "ioread32",
      "external": true,
      "loc": "lib/iomap.c:88",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347440,
      "name": "ioread32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<b>Param type changed. </b>
<code>void * addr</code> ➡️ <code>const void * addr</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
unsigned int ioread32(void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int ioread32(void * addr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int ioread32(void * addr)
```
</details>
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
