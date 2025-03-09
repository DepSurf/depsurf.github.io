# Function: <code>vfio_noiommu_ioctl</code>

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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036832,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:187",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036832,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587866880,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:188",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866880,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587927216,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:188",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587927216,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587809408,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:178",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809408,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:251",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414640,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071592547905,
      "name": "vfio_noiommu_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:180",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815520,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071594427294,
      "name": "vfio_noiommu_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293360128,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:187",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293360128,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684752,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:187",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684752,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991392,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:187",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991392,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_noiommu_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098560,
      "name": "vfio_noiommu_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:187",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098560,
      "name": "vfio_noiommu_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
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
long int vfio_noiommu_ioctl(void * iommu_data, unsigned int cmd, long unsigned int arg)
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
