# Function: <code>pci_intx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253680,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:3251",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253680,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563328,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:3561",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563328,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700112,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:3599",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700112,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745136,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:3737",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745136,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584003392,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:3752",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003392,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584198320,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:3957",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198320,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584287776,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4222",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287776,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584482656,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4320",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482656,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618112,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618112,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296528,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4387",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296528,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585451312,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4462",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451312,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331376,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4511",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331376,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789376,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4561",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789376,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586975232,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4657",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975232,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140560,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4600",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140560,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588416192,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4638",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416192,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588711520,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4748",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711520,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496859064,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496859064,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230139664,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230139664,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290940912,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290940912,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275561564,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275561564,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570272,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570272,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584498432,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498432,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584568272,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_remove",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568272,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void pci_intx(struct pci_dev * pdev, int enable)
```

```json
{
  "name": "pci_intx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676256,
      "name": "pci_intx",
      "external": true,
      "loc": "drivers/pci/pci.c:4316",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676256,
      "name": "pci_intx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
