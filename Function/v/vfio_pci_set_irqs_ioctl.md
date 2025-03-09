# Function: <code>vfio_pci_set_irqs_ioctl</code>

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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074704,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:622",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074704,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587917776,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:636",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917776,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587978944,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:638",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978944,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587861360,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:638",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861360,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_core_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588466320,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:638",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466320,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_core_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868912,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:638",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868912,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293408432,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:622",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293408432,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722624,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:622",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722624,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029264,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:622",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029264,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```

```json
{
  "name": "vfio_pci_set_irqs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136432,
      "name": "vfio_pci_set_irqs_ioctl",
      "external": true,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:622",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136432,
      "name": "vfio_pci_set_irqs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_core_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
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
int vfio_pci_set_irqs_ioctl(struct vfio_pci_device * vdev, uint32_t flags, unsigned int index, unsigned int start, unsigned int count, void * data)
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
