# Function: <code>vfio_pci_ioctl</code>

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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063520,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:691",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063520,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3240
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904816,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:760",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904816,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3907
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966208,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:800",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966208,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4163
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
long int vfio_pci_ioctl(struct vfio_device * core_vdev, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587847872,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:782",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847872,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4149
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293392800,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:691",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293392800,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3800
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711440,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:691",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711440,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3240
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587018080,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:691",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018080,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3240
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_pci_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587125248,
      "name": "vfio_pci_ioctl",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:691",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587125248,
      "name": "vfio_pci_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3240
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
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
long int vfio_pci_ioctl(struct vfio_device * core_vdev, unsigned int cmd, long unsigned int arg)
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
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
long int vfio_pci_ioctl(void * device_data, unsigned int cmd, long unsigned int arg)
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
