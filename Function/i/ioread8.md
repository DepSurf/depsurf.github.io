# Function: <code>ioread8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049392,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:71",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/char/tpm/tpm_tis.c:get_burstcount",
        "drivers/char/tpm/tpm_tis.c:get_burstcount",
        "drivers/char/tpm/tpm_tis.c:recv_data",
        "drivers/char/tpm/tpm_tis.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/ata_generic.c:generic_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049392,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343456,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:71",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343456,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468832,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:71",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468832,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491072,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:71",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491072,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672112,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:72",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672112,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583889888,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:72",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889888,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974128,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:72",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974128,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156240,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156240,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289984,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289984,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700256,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:atapi_pio_bytes",
        "drivers/ata/libata-sff.c:atapi_send_cdb",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700256,
      "name": "ioread8",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584813552,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:atapi_pio_bytes",
        "drivers/ata/libata-sff.c:atapi_send_cdb",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813552,
      "name": "ioread8",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858112,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858112,
      "name": "ioread8",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279568,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279568,
      "name": "ioread8",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130896,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130896,
      "name": "ioread8",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587121728,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:79",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread8",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587121728,
      "name": "ioread8",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383936,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:79",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread8",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383936,
      "name": "ioread8",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread8(const void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718288,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:79",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread8",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sectors",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718288,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
  "name": "ioread8",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496643100,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496957988,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511104308,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pci/controller/dwc/pci-layerscape.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498180788,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498185468,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498188408,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498610464,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498816680,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499795880,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500098448,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501526276,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501582772,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
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
  "name": "ioread8",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229740328,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/irqchip/irq-renesas-intc-irqpin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read8"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955584,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229963996,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pinctrl/sh-pfc/pfc-r8a7740.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_get_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3229965224,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pinctrl/sh-pfc/pfc-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_get_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3230224484,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 3230945336,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230949264,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952716,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3231231756,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231428276,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 3231789808,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_lcd_set_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3232236708,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3234043604,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234093868,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/clocksource/sh_mtu2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 3234094828,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290444304,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290444304,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
  "name": "ioread8",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275629752,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275961656,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275965650,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969268,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276197782,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276314242,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276946958,
      "name": "ioread8",
      "external": false,
      "loc": "include/asm-generic/io.h:686",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt"
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258720,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258720,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193920,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193920,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242480,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242480,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```

```json
{
  "name": "ioread8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347312,
      "name": "ioread8",
      "external": true,
      "loc": "lib/iomap.c:73",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_get_status",
        "drivers/virtio/virtio_pci_modern.c:vp_generation",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_common.c:vp_interrupt",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_get",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_bmdma_status",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_sff_wait_after_reset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/ata_generic.c:generic_set_mode",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347312,
      "name": "ioread8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
unsigned int ioread8(void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int ioread8(void * addr)
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
unsigned int ioread8(void * addr)
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
