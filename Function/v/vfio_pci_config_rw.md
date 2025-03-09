# Function: <code>vfio_pci_config_rw</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085168,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1832",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085168,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587930480,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1881",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930480,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991728,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1888",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991728,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587874208,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1888",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874208,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
ssize_t vfio_pci_config_rw(struct vfio_pci_core_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588481024,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1888",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481024,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
ssize_t vfio_pci_config_rw(struct vfio_pci_core_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589884704,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1938",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589884704,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293423328,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1832",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293423328,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1256
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586733088,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1832",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733088,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039728,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1832",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039728,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```

```json
{
  "name": "vfio_pci_config_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587146896,
      "name": "vfio_pci_config_rw",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:1832",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587146896,
      "name": "vfio_pci_config_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
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
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device * vdev</code> ➡️ <code>struct vfio_pci_core_device * vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
ssize_t vfio_pci_config_rw(struct vfio_pci_core_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
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
ssize_t vfio_pci_config_rw(struct vfio_pci_device * vdev, char * buf, size_t count, loff_t * ppos, bool iswrite)
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
