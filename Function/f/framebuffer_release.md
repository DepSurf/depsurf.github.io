# Function: <code>framebuffer_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583502320,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:81",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502320,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822992,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:81",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822992,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583962240,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:81",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962240,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584013888,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:81",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013888,
      "name": "framebuffer_release",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584229824,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:81",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229824,
      "name": "framebuffer_release",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584450096,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:82",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450096,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546752,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:82",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546752,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584744592,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744592,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584879376,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879376,
      "name": "framebuffer_release",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585575872,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575872,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585709328,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709328,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585589744,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585589744,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586065344,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/efifb.c:efifb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586065344,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587283184,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283184,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522704,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522704,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588801232,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588801232,
      "name": "framebuffer_release",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082416,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fb_info.c:65",
      "file": "drivers/video/fbdev/core/fb_info.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_alloc_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082416,
      "name": "framebuffer_release",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497275272,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497275272,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230452568,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230452568,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291254592,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/gxt4500.c:gxt4500_remove",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_destroy",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291254592,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275809284,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275809284,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584830560,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830560,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584760416,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760416,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584831984,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831984,
      "name": "framebuffer_release",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void framebuffer_release(struct fb_info * info)
```

```json
{
  "name": "framebuffer_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584937056,
      "name": "framebuffer_release",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbsysfs.c:79",
      "file": "drivers/video/fbdev/core/fbsysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_remove",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584937056,
      "name": "framebuffer_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
