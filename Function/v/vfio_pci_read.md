# Function: <code>vfio_pci_read</code>

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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063456,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1177",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063456,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587902688,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1362",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902688,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587963280,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1439",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963280,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t vfio_pci_read(struct vfio_device * core_vdev, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587845712,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1413",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845712,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293392672,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1177",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293392672,
      "name": "vfio_pci_read",
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586711376,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1177",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711376,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018016,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1177",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018016,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "vfio_pci_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587125184,
      "name": "vfio_pci_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1177",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587125184,
      "name": "vfio_pci_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_device * core_vdev</code>
</li>
<li>
<b>Param removed. </b>
<code>void * device_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
ssize_t vfio_pci_read(struct vfio_device * core_vdev, char * buf, size_t count, loff_t * ppos)
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
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
ssize_t vfio_pci_read(void * device_data, char * buf, size_t count, loff_t * ppos)
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
