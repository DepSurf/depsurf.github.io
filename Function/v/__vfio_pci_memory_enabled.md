# Function: <code>__vfio_pci_memory_enabled</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device * vdev)
```

```json
{
  "name": "__vfio_pci_memory_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929456,
      "name": "__vfio_pci_memory_enabled",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:399",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929456,
      "name": "__vfio_pci_memory_enabled",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device * vdev)
```

```json
{
  "name": "__vfio_pci_memory_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587990688,
      "name": "__vfio_pci_memory_enabled",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:399",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587990688,
      "name": "__vfio_pci_memory_enabled",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device * vdev)
```

```json
{
  "name": "__vfio_pci_memory_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587873136,
      "name": "__vfio_pci_memory_enabled",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:399",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873136,
      "name": "__vfio_pci_memory_enabled",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_core_device * vdev)
```

```json
{
  "name": "__vfio_pci_memory_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588479936,
      "name": "__vfio_pci_memory_enabled",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:399",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479936,
      "name": "__vfio_pci_memory_enabled",
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
bool __vfio_pci_memory_enabled(struct vfio_pci_core_device * vdev)
```

```json
{
  "name": "__vfio_pci_memory_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589883520,
      "name": "__vfio_pci_memory_enabled",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:399",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883520,
      "name": "__vfio_pci_memory_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device * vdev)
```
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
bool __vfio_pci_memory_enabled(struct vfio_pci_core_device * vdev)
```
</details>
</li>
</ul>
