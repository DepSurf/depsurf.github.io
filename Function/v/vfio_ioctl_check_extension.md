# Function: <code>vfio_ioctl_check_extension</code>

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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038976,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1025",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038976,
      "name": "vfio_ioctl_check_extension",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868880,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1040",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868880,
      "name": "vfio_ioctl_check_extension",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929312,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1041",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929312,
      "name": "vfio_ioctl_check_extension",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587811456,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:935",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587811456,
      "name": "vfio_ioctl_check_extension",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1021",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588415248,
      "name": "vfio_ioctl_check_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071592547960,
      "name": "vfio_ioctl_check_extension.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:708",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_file_enforced_coherent",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815616,
      "name": "vfio_ioctl_check_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071594427322,
      "name": "vfio_ioctl_check_extension.cold",
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293366512,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1025",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293366512,
      "name": "vfio_ioctl_check_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686896,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1025",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686896,
      "name": "vfio_ioctl_check_extension",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993536,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1025",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993536,
      "name": "vfio_ioctl_check_extension",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```

```json
{
  "name": "vfio_ioctl_check_extension",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587100704,
      "name": "vfio_ioctl_check_extension",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1025",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_external_check_extension",
        "drivers/vfio/vfio.c:vfio_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587100704,
      "name": "vfio_ioctl_check_extension",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
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
long int vfio_ioctl_check_extension(struct vfio_container * container, long unsigned int arg)
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
