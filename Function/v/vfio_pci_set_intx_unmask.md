# Function: <code>vfio_pci_set_intx_unmask</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587074560,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:404",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074560,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587917552,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:418",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917552,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587978720,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:420",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978720,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587861136,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:420",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861136,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_core_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588464879,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:420",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464832,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071592551319,
      "name": "vfio_pci_set_intx_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int vfio_pci_set_intx_unmask(struct vfio_pci_core_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:420",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589867328,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071594430669,
      "name": "vfio_pci_set_intx_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293408160,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:404",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293408160,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586722480,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:404",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722480,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587029120,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:404",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029120,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_intx_unmask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587136288,
      "name": "vfio_pci_set_intx_unmask",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:404",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136288,
      "name": "vfio_pci_set_intx_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
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
int vfio_pci_set_intx_unmask(struct vfio_pci_core_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
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
int vfio_pci_set_intx_unmask(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
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
