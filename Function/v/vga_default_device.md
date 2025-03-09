# Function: <code>vga_default_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584345008,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:135",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345008,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595476333,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:135",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397280,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595729051,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:156",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598256,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596654784,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:156",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:hibmc_fixup_vgaarb",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681776,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586116976,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:156",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114000,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603156539,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:156",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586362384,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604961431,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:156",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503616,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605070036,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749056,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605107421,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895488,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609387983,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706544,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612459438,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587766864,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614601545,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:159",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646112,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615558820,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:156",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232672,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587185184,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/pci/vgaarb.c:134",
      "file": "drivers/pci/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_arb_open",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/pci/vgaarb.c:vga_put",
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180768,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588407504,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/pci/vgaarb.c:134",
      "file": "drivers/pci/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_arb_open",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/pci/vgaarb.c:vga_put",
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402400,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588682432,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/pci/vgaarb.c:134",
      "file": "drivers/pci/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_arb_open",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/pci/vgaarb.c:vga_put",
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/video/aperture.c:aperture_remove_conflicting_pci_devices",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588678320,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588982847,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/pci/vgaarb.c:132",
      "file": "drivers/pci/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_arb_open",
        "drivers/pci/vgaarb.c:vga_arb_write",
        "drivers/pci/vgaarb.c:vga_arbiter_add_pci_device",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/pci/vgaarb.c:vga_put",
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/video/aperture.c:aperture_remove_conflicting_pci_devices",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_client_probe_defer",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979136,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511238656,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499852416,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243884904,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232286900,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302804496,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293173728,
      "name": "vga_default_device",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270812410,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276964334,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605007514,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652576,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604971845,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586520912,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605087960,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850048,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct pci_dev * vga_default_device()
```

```json
{
  "name": "vga_default_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605111615,
      "name": "vga_default_device",
      "external": true,
      "loc": "drivers/gpu/vga/vgaarb.c:158",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_register_client",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/pci/fixup.c:pci_fixup_video",
        "arch/x86/video/fbdev.c:fb_is_primary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956160,
      "name": "vga_default_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
