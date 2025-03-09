# Function: <code>remove_conflicting_pci_framebuffers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584530320,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1878",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584530320,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1780",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584729575,
      "name": "remove_conflicting_pci_framebuffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584728080,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865678,
      "name": "remove_conflicting_pci_framebuffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584864784,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560064,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1776",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560064,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585694160,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1769",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694160,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585574720,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1767",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574720,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586049264,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1820",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049264,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587269968,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1801",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269968,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497248248,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497248248,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230434512,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230434512,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291231232,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291231232,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275794870,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275794870,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816862,
      "name": "remove_conflicting_pci_framebuffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584815968,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747630,
      "name": "remove_conflicting_pci_framebuffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584746736,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584818286,
      "name": "remove_conflicting_pci_framebuffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584817392,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```

```json
{
  "name": "remove_conflicting_pci_framebuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_conflicting_pci_framebuffers",
      "external": true,
      "loc": "drivers/video/fbdev/core/fbmem.c:1770",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923358,
      "name": "remove_conflicting_pci_framebuffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071584922464,
      "name": "remove_conflicting_pci_framebuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, int res_id, const char * name)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int res_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>pdev, res_id, name</code> ➡️ <code>pdev, name</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev * pdev, const char * name)
```
</details>
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
