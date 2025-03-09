# Function: <code>pci_unmap_rom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583289184,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:181",
      "file": "drivers/pci/rom.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289184,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600320,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:169",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600320,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737488,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:174",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737488,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779296,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:174",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779296,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584039424,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:181",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039424,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236224,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:180",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236224,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325888,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325888,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584521072,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521072,
      "name": "pci_unmap_rom",
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584656192,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656192,
      "name": "pci_unmap_rom",
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340128,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340128,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493232,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493232,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372592,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372592,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585833344,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833344,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025040,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025040,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588201696,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588201696,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477376,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477376,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774720,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774720,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496903824,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496903824,
      "name": "pci_unmap_rom",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230180216,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230180216,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290996352,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290996352,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275592678,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275592678,
      "name": "pci_unmap_rom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584606656,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606656,
      "name": "pci_unmap_rom",
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536480,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536480,
      "name": "pci_unmap_rom",
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584606352,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606352,
      "name": "pci_unmap_rom",
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
void pci_unmap_rom(struct pci_dev * pdev, void * rom)
```

```json
{
  "name": "pci_unmap_rom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714048,
      "name": "pci_unmap_rom",
      "external": true,
      "loc": "drivers/pci/rom.c:187",
      "file": "drivers/pci/rom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714048,
      "name": "pci_unmap_rom",
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
