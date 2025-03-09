# Function: <code>iowrite32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049712,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:124",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049712,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343776,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:124",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343776,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469152,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:124",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469152,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491392,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:124",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491392,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672432,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:125",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672432,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890208,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:125",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890208,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974448,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:125",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974448,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156720,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156720,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290464,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290464,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701440,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701440,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814736,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814736,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859296,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859296,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280752,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_finalize_features",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280752,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586132288,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132288,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123280,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:221",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32le",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123280,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385488,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:221",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features",
        "drivers/virtio/virtio_pci_modern.c:vp_notify_with_data",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/char/tpm/tpm_crb.c:crb_try_pluton_doorbell",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32le",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385488,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719840,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:221",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features",
        "drivers/virtio/virtio_pci_modern.c:vp_notify_with_data",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_relinquish_locality",
        "drivers/char/tpm/tpm_crb.c:crb_request_locality",
        "drivers/char/tpm/tpm_crb.c:crb_cmd_ready",
        "drivers/char/tpm/tpm_crb.c:crb_go_idle",
        "drivers/char/tpm/tpm_crb.c:crb_try_pluton_doorbell",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32le",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719840,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
  "name": "iowrite32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496409304,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496447972,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/bus/brcmstb_gisb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496644408,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_write",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496800992,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/gpio/gpio-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xgene.c:xgene_gpio_resume",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in",
        "drivers/gpio/gpio-xgene.c:__xgene_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496968048,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497181984,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pci/controller/dwc/pci-layerscape.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init",
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497792176,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497792816,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-qoriq.c:mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498143640,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_enable_wdt_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498143856,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498182004,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498188364,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498817084,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498818688,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499794656,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500042376,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/net/ethernet/freescale/xgmac_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500098376,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501259720,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/edac/altera_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/altera_edac.c:altr_sdram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501521060,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501527300,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501575004,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501584128,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_enable",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_enable",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501737208,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/memory/fsl_ifc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
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
  "name": "iowrite32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224587816,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "arch/arm/mach-npcm/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 3243350036,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "arch/arm/mach-shmobile/setup-r8a7740.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_generic_init",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of"
      ],
      "caller_func": []
    },
    {
      "addr": 3243351004,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "arch/arm/mach-shmobile/setup-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243353648,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "arch/arm/mach-shmobile/smp-emev2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3229740908,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/irqchip/irq-renesas-intc-irqpin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 3229744784,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3229761380,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/bus/brcmstb_gisb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/brcmstb_gisb.c:gisb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3229927448,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_unmask",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_mask",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_ack",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3229956688,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_write",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3229964792,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pinctrl/sh-pfc/pfc-r8a7778.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3229965352,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pinctrl/sh-pfc/pfc-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230231852,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230325416,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pci/controller/pci-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_cfg_base"
      ],
      "caller_func": []
    },
    {
      "addr": 3230616996,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230619520,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-qoriq.c:mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230893448,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_enable_wdt_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230893584,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3230946668,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952660,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ],
      "caller_func": []
    },
    {
      "addr": 3231428484,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 3231458220,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/iommu/ipmmu-vmsa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_resume_noirq",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_remove",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_detach_device",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_irq",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_utlb_enable",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_utlb_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232230316,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3232559808,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/net/ethernet/freescale/xgmac_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 3234036064,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3234043996,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234087328,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 3234095960,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_enable",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_enable",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 3234098576,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clocksource/em_sti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/em_sti.c:em_sti_clock_event_next",
        "drivers/clocksource/em_sti.c:em_sti_clock_event_next",
        "drivers/clocksource/em_sti.c:em_sti_clock_event_next",
        "drivers/clocksource/em_sti.c:em_sti_clock_event_next",
        "drivers/clocksource/em_sti.c:em_sti_clock_event_next",
        "drivers/clocksource/em_sti.c:em_sti_stop",
        "drivers/clocksource/em_sti.c:em_sti_start",
        "drivers/clocksource/em_sti.c:em_sti_start",
        "drivers/clocksource/em_sti.c:em_sti_start",
        "drivers/clocksource/em_sti.c:em_sti_start",
        "drivers/clocksource/em_sti.c:em_sti_start"
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290449440,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_finalize_features",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290449440,
      "name": "iowrite32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
  "name": "iowrite32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275636312,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275927480,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275961808,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_iowrite64_twopart",
        "drivers/virtio/virtio_pci_modern.c:vp_iowrite64_twopart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969288,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276314592,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276940088,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277004858,
      "name": "iowrite32",
      "external": false,
      "loc": "include/asm-generic/io.h:736",
      "file": "drivers/spi/spi-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-sifive.c:sifive_spi_remove",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/spi/spi-sifive.c:sifive_spi_set_cs",
        "drivers/spi/spi-sifive.c:sifive_spi_prepare_message",
        "drivers/spi/spi-sifive.c:sifive_spi_prepare_message",
        "drivers/spi/spi-sifive.c:sifive_spi_prepare_message"
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259200,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259200,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194400,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194400,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242960,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242960,
      "name": "iowrite32",
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
void iowrite32(u32 val, void * addr)
```

```json
{
  "name": "iowrite32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347792,
      "name": "iowrite32",
      "external": true,
      "loc": "lib/iomap.c:201",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_finalize_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write32",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_write",
        "drivers/ata/ata_piix.c:piix_sidpr_scr_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347792,
      "name": "iowrite32",
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
void iowrite32(u32 val, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iowrite32(u32 val, void * addr)
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
void iowrite32(u32 val, void * addr)
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
