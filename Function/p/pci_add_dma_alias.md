# Function: <code>pci_add_dma_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583581856,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:4900",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583581856,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718800,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:4908",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718800,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583759552,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:5066",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759552,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018928,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:5090",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018928,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215760,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:5470",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215760,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584305792,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:5782",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305792,
      "name": "pci_add_dma_alias",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:5878",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501686,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584499136,
      "name": "pci_add_dma_alias",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637573,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584635056,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6048",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320411,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585318112,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591395194,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585473088,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6171",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337509,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585352944,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6361",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364850,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585811936,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6457",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594227116,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071587001008,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588169680,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6404",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588169680,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588445728,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6526",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588445728,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588742592,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6670",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd/iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742592,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496882192,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496882192,
      "name": "pci_add_dma_alias",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230159284,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230159284,
      "name": "pci_add_dma_alias",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290967216,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290967216,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275579800,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275579800,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589733,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584587216,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584517861,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584515344,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587733,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584585216,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn_from, unsigned int nr_devfns)
```

```json
{
  "name": "pci_add_dma_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_add_dma_alias",
      "external": true,
      "loc": "drivers/pci/pci.c:6027",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_plx_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_pex_vca_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_mic_x200_dma_alias",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:quirk_dma_func1_alias",
        "drivers/pci/quirks.c:quirk_dma_func0_alias",
        "drivers/iommu/amd_iommu.c:setup_aliases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695429,
      "name": "pci_add_dma_alias.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584692880,
      "name": "pci_add_dma_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void pci_add_dma_alias(struct pci_dev * dev, u8 devfn)
```
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 devfn_from</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_devfns</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 devfn</code>
</li>
</ul>
</details>
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
