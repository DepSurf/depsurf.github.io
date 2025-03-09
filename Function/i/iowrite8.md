# Function: <code>iowrite8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049584,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:112",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_remove",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049584,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343648,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:112",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343648,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469024,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:112",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469024,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491264,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:112",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491264,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672304,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:113",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672304,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890080,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:113",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890080,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974320,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:113",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974320,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156592,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156592,
      "name": "iowrite8",
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290336,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290336,
      "name": "iowrite8",
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701280,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_irq_on",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701280,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814576,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_irq_on",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814576,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859136,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_irq_on",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859136,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280592,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_irq_on",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280592,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586132032,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132032,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587122992,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:203",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite8",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122992,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385200,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:203",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite8",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385200,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719552,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:203",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite8",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_thaw",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719552,
      "name": "iowrite8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
  "name": "iowrite8",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496643256,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497182044,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/pci/controller/dwc/pci-layerscape.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498180768,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498189008,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498816828,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499795592,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_postreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_freeze",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500098400,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501526228,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501582868,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
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
  "name": "iowrite8",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243350216,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "arch/arm/mach-shmobile/setup-r8a7740.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of"
      ],
      "caller_func": []
    },
    {
      "addr": 3229740956,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/irqchip/irq-renesas-intc-irqpin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_write8"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955692,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229964036,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/pinctrl/sh-pfc/pfc-r8a7740.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_set_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3229965264,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/pinctrl/sh-pfc/pfc-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_set_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3230945300,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3230953192,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3231428572,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 3231792544,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_lcd_set_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3232235392,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3232406508,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/mtd/nand/raw/omap2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf8"
      ],
      "caller_func": []
    },
    {
      "addr": 3234043636,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234093880,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/clocksource/sh_mtu2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 3234094896,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290443184,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set_status",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290443184,
      "name": "iowrite8",
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
  "name": "iowrite8",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275961596,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969776,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276314342,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276945784,
      "name": "iowrite8",
      "external": false,
      "loc": "include/asm-generic/io.h:720",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259072,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259072,
      "name": "iowrite8",
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194272,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194272,
      "name": "iowrite8",
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242832,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242832,
      "name": "iowrite8",
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
void iowrite8(u8 val, void * addr)
```

```json
{
  "name": "iowrite8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347664,
      "name": "iowrite8",
      "external": true,
      "loc": "lib/iomap.c:189",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_reset",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_legacy.c:vp_reset",
        "drivers/virtio/virtio_pci_legacy.c:vp_set",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes",
        "drivers/ata/libata-sff.c:ata_bmdma_stop",
        "drivers/ata/libata-sff.c:ata_bmdma_start",
        "drivers/ata/libata-sff.c:ata_bmdma_setup",
        "drivers/ata/libata-sff.c:ata_bmdma_irq_clear",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_devchk",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_read",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_set_devctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347664,
      "name": "iowrite8",
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
void iowrite8(u8 val, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iowrite8(u8 val, void * addr)
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
void iowrite8(u8 val, void * addr)
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
