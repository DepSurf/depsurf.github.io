# Function: <code>vfio_pci_setup_barmap</code>

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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074960,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:132",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074960,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918032,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:203",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918032,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587979152,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:203",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979152,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587861568,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:203",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861568,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int vfio_pci_setup_barmap(struct vfio_pci_core_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:203",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466528,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071592551555,
      "name": "vfio_pci_setup_barmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int vfio_pci_setup_barmap(struct vfio_pci_core_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:203",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869216,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071594430907,
      "name": "vfio_pci_setup_barmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293408768,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:132",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293408768,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722880,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:132",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722880,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029520,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:132",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029520,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```

```json
{
  "name": "vfio_pci_setup_barmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136688,
      "name": "vfio_pci_setup_barmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:132",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136688,
      "name": "vfio_pci_setup_barmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
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
int vfio_pci_setup_barmap(struct vfio_pci_core_device * vdev, int bar)
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
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
int vfio_pci_setup_barmap(struct vfio_pci_device * vdev, int bar)
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
