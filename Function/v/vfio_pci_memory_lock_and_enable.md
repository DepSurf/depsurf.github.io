# Function: <code>vfio_pci_memory_lock_and_enable</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_memory_lock_and_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587905716,
      "name": "vfio_pci_memory_lock_and_enable",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:1478",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912640,
      "name": "vfio_pci_memory_lock_and_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_memory_lock_and_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587967219,
      "name": "vfio_pci_memory_lock_and_enable",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:1553",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974384,
      "name": "vfio_pci_memory_lock_and_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_device * vdev)
```

```json
{
  "name": "vfio_pci_memory_lock_and_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587848910,
      "name": "vfio_pci_memory_lock_and_enable",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci.c:1533",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856768,
      "name": "vfio_pci_memory_lock_and_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_core_device * vdev)
```

```json
{
  "name": "vfio_pci_memory_lock_and_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588455024,
      "name": "vfio_pci_memory_lock_and_enable",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:1335",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461328,
      "name": "vfio_pci_memory_lock_and_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_core_device * vdev)
```

```json
{
  "name": "vfio_pci_memory_lock_and_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589859824,
      "name": "vfio_pci_memory_lock_and_enable",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:1365",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859824,
      "name": "vfio_pci_memory_lock_and_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_device * vdev)
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
u16 vfio_pci_memory_lock_and_enable(struct vfio_pci_core_device * vdev)
```
</details>
</li>
</ul>
