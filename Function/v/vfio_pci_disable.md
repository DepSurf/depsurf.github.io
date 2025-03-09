# Function: <code>vfio_pci_disable</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:368",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067984,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
    },
    {
      "addr": 18446744071587070679,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:377",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910560,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446744071587913213,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:419",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972320,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446744071591535083,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:400",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854400,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
    },
    {
      "addr": 18446744071591477375,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293398576,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:368",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293398576,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:368",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715904,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
    },
    {
      "addr": 18446744071586718599,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:368",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022544,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
    },
    {
      "addr": 18446744071587025239,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void vfio_pci_disable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_disable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:368",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129712,
      "name": "vfio_pci_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
    },
    {
      "addr": 18446744071587132407,
      "name": "vfio_pci_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
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
void vfio_pci_disable(struct vfio_pci_device * vdev)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void vfio_pci_disable(struct vfio_pci_device * vdev)
```
</details>
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
