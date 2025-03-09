# Function: <code>pci_release_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583254176,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:2795",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254176,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563808,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:2973",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563808,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700592,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3011",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700592,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740400,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3028",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740400,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998992,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3138",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998992,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197472,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3284",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197472,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286896,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3549",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286896,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584481856,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3670",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481856,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617312,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617312,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297952,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3736",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297952,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452736,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3800",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452736,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585332096,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3831",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585332096,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3881",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592363767,
      "name": "pci_release_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585789568,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3975",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594225777,
      "name": "pci_release_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586975952,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3918",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596208290,
      "name": "pci_release_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588140992,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3956",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596733448,
      "name": "pci_release_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588416608,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:4070",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_remove",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597641871,
      "name": "pci_release_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588711936,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496857896,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496857896,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230138744,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230138744,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290939424,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290939424,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275560538,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275560538,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569472,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569472,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584497632,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584497632,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584567472,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567472,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void pci_release_region(struct pci_dev * pdev, int bar)
```

```json
{
  "name": "pci_release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584675456,
      "name": "pci_release_region",
      "external": true,
      "loc": "drivers/pci/pci.c:3666",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:pcim_iounmap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "lib/devres.c:pcim_iomap_regions",
        "drivers/pci/pci.c:pci_release_regions",
        "drivers/pci/pci.c:__pci_request_selected_regions",
        "drivers/pci/pci.c:pcim_release",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_remove",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584675456,
      "name": "pci_release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
