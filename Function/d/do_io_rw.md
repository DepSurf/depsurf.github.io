# Function: <code>do_io_rw</code>

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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075120,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:46",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075120,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
ssize_t do_io_rw(struct vfio_pci_device * vdev, bool test_mem, void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918528,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:97",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918528,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
ssize_t do_io_rw(struct vfio_pci_device * vdev, bool test_mem, void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587979808,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:97",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587979808,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
ssize_t do_io_rw(struct vfio_pci_device * vdev, bool test_mem, void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862240,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:97",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862240,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1262
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
ssize_t do_io_rw(struct vfio_pci_core_device * vdev, bool test_mem, void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588467344,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:97",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467344,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1262
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
ssize_t do_io_rw(struct vfio_pci_core_device * vdev, bool test_mem, void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589870128,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:97",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589870128,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293409040,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:46",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293409040,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723040,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:46",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723040,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029680,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:46",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029680,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```

```json
{
  "name": "do_io_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136848,
      "name": "do_io_rw",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_rdwr.c:46",
      "file": "drivers/vfio/pci/vfio_pci_rdwr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136848,
      "name": "do_io_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_pci_device * vdev</code>
</li>
<li>
<b>Param added. </b>
<code>bool test_mem</code>
</li>
<li>
<b>Param reordered. </b>
<code>io, buf, off, count, x_start, x_end, iswrite</code> ➡️ <code>vdev, test_mem, io, buf, off, count, x_start, x_end, iswrite</code>
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
ssize_t do_io_rw(struct vfio_pci_core_device * vdev, bool test_mem, void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
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
ssize_t do_io_rw(void * io, char * buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite)
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
