# Function: <code>vfio_pci_enable</code>

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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:261",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069232,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    },
    {
      "addr": 18446744071587070733,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:270",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911440,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071587913267,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:312",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973184,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071591535137,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:312",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855264,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
    },
    {
      "addr": 18446744071591477429,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293400384,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:261",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293400384,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:261",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717152,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    },
    {
      "addr": 18446744071586718653,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:261",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023792,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    },
    {
      "addr": 18446744071587025293,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:261",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130960,
      "name": "vfio_pci_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    },
    {
      "addr": 18446744071587132461,
      "name": "vfio_pci_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_enable(struct vfio_pci_device * vdev)
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
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
int vfio_pci_enable(struct vfio_pci_device * vdev)
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
