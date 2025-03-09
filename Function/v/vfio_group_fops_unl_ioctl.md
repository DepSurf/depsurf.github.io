# Function: <code>vfio_group_fops_unl_ioctl</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1513",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045552,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071587046817,
      "name": "vfio_group_fops_unl_ioctl.cold",
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877056,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1517",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877056,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937520,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1518",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937520,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587818608,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1417",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587818608,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422384,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1519",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422384,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820624,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1196",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820624,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293367056,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1513",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293367056,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2324
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1513",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586693472,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071586694737,
      "name": "vfio_group_fops_unl_ioctl.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1513",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000112,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071587001377,
      "name": "vfio_group_fops_unl_ioctl.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfio_group_fops_unl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_group_fops_unl_ioctl",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1513",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107280,
      "name": "vfio_group_fops_unl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071587108545,
      "name": "vfio_group_fops_unl_ioctl.cold",
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
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
long int vfio_group_fops_unl_ioctl(struct file * filep, unsigned int cmd, long unsigned int arg)
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
