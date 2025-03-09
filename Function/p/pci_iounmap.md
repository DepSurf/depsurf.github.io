# Function: <code>pci_iounmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049920,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:247",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049920,
      "name": "pci_iounmap",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344112,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:247",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344112,
      "name": "pci_iounmap",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469488,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:247",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469488,
      "name": "pci_iounmap",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491728,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:247",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491728,
      "name": "pci_iounmap",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672768,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:248",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672768,
      "name": "pci_iounmap",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890544,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:248",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890544,
      "name": "pci_iounmap",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974784,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:248",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974784,
      "name": "pci_iounmap",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157520,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157520,
      "name": "pci_iounmap",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291264,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291264,
      "name": "pci_iounmap",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700176,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700176,
      "name": "pci_iounmap",
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584813472,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813472,
      "name": "pci_iounmap",
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858032,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858032,
      "name": "pci_iounmap",
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279488,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279488,
      "name": "pci_iounmap",
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131312,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131312,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587122192,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:424",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122192,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587384400,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:424",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384400,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718752,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:424",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/pci/quirks.c:nvme_disable_and_flr",
        "drivers/pci/quirks.c:reset_ivb_igd",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718752,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
  "name": "pci_iounmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/tty/serial/8250/8250_pci.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224480848,
      "name": "pci_iounmap",
      "external": true,
      "loc": "arch/arm/mm/iomap.c:36",
      "file": "arch/arm/mm/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224480848,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290441632,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap",
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290441632,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
  "name": "pci_iounmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_iounmap",
      "external": false,
      "loc": "include/asm-generic/io.h:896",
      "file": "drivers/tty/serial/8250/8250_pci.c",
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260000,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260000,
      "name": "pci_iounmap",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195200,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195200,
      "name": "pci_iounmap",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243760,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243760,
      "name": "pci_iounmap",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
```

```json
{
  "name": "pci_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348592,
      "name": "pci_iounmap",
      "external": true,
      "loc": "lib/iomap.c:380",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iomap_release",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348592,
      "name": "pci_iounmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void pci_iounmap(struct pci_dev * dev, void * addr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pci_iounmap(struct pci_dev * dev, void * addr)
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
