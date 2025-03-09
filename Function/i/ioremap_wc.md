# Function: <code>ioremap_wc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286816,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:289",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286816,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286480,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:288",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286480,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301872,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:288",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301872,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299616,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:289",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299616,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320336,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:341",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320336,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331104,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:341",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331104,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357328,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:342",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357328,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371488,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:362",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371488,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376096,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376096,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404688,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404688,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405264,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405264,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408496,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:386",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408496,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471120,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:386",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/pci/pci.c:pci_ioremap_wc_bar",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471120,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548400,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:391",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/pci/pci.c:pci_ioremap_wc_bar",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548400,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653392,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:398",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/pci/pci.c:pci_ioremap_wc_bar",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653392,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667616,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:403",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/pci/pci.c:pci_ioremap_wc_bar",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667616,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702176,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:403",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc",
        "lib/devres.c:devm_ioremap_wc",
        "drivers/pci/pci.c:pci_ioremap_wc_bar",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702176,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * ioremap_wc(resource_size_t res_cookie, size_t size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224498796,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/arm/mm/ioremap.c:395",
      "file": "arch/arm/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "fs/pstore/ram_core.c:persistent_ram_new",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_map_angle",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224498796,
      "name": "ioremap_wc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * ioremap_wc(phys_addr_t addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282725984,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/powerpc/mm/ioremap.c:22",
      "file": "arch/powerpc/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282725984,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372000,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372000,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302192,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302192,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371920,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371920,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_wc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380400,
      "name": "ioremap_wc",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:384",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380400,
      "name": "ioremap_wc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t res_cookie</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t addr</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * ioremap_wc(resource_size_t phys_addr, long unsigned int size)
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
