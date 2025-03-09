# Function: <code>ioread16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049456,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:76",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/ata/libata-sff.c:ata_sff_drain_fifo",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049456,
      "name": "ioread16",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343520,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:76",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/ata/libata-sff.c:ata_sff_drain_fifo",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343520,
      "name": "ioread16",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468896,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:76",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/ata/libata-sff.c:ata_sff_drain_fifo",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468896,
      "name": "ioread16",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491136,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:76",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491136,
      "name": "ioread16",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672176,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:77",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672176,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583889952,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:77",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889952,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974192,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:77",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974192,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156304,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156304,
      "name": "ioread16",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290048,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290048,
      "name": "ioread16",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700368,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700368,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584813664,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813664,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858224,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858224,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279680,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279680,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131040,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131040,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587121888,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:85",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread16le",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587121888,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587384096,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:85",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread16le",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384096,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
unsigned int ioread16(const void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718448,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:85",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_avq_index",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_avq_num",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread16le",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718448,
      "name": "ioread16",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ioread16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496643064,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496958196,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498181296,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498189144,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498816900,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499790840,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500097752,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_mii_out",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501526376,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501574796,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501584072,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next"
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
  "name": "ioread16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229860384,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/pinctrl/pinctrl-rza1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_set",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get_direction",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955568,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230224740,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 3243763844,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/clk/renesas/clk-rz.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230944852,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952904,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 3231428336,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 3231772348,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/mfd/asic3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/asic3.c:asic3_clk_disable",
        "drivers/mfd/asic3.c:asic3_clk_enable",
        "drivers/mfd/asic3.c:asic3_gpio_set",
        "drivers/mfd/asic3.c:asic3_gpio_get",
        "drivers/mfd/asic3.c:asic3_gpio_direction",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_unmask_irq",
        "drivers/mfd/asic3.c:asic3_unmask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_mask_irq",
        "drivers/mfd/asic3.c:asic3_mask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_set_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3231789784,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232235480,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234043720,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234087056,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/clocksource/sh_mtu2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234095912,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next"
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
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290445552,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290445552,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
  "name": "ioread16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275629928,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275961246,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969434,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276314442,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276945898,
      "name": "ioread16",
      "external": false,
      "loc": "include/asm-generic/io.h:694",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258784,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258784,
      "name": "ioread16",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193984,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193984,
      "name": "ioread16",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242544,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242544,
      "name": "ioread16",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int ioread16(void * addr)
```

```json
{
  "name": "ioread16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347376,
      "name": "ioread16",
      "external": true,
      "loc": "lib/iomap.c:78",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347376,
      "name": "ioread16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
unsigned int ioread16(void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int ioread16(void * addr)
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
unsigned int ioread16(void * addr)
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
