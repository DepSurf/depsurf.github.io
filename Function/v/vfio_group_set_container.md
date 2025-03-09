# Function: <code>vfio_group_set_container</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587045668,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1369",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vfio_group_set_container(struct vfio_group * group, int container_fd)
```

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876592,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1373",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876592,
      "name": "vfio_group_set_container",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int vfio_group_set_container(struct vfio_group * group, int container_fd)
```

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937056,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1374",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937056,
      "name": "vfio_group_set_container",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int vfio_group_set_container(struct vfio_group * group, int container_fd)
```

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587818144,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1273",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587818144,
      "name": "vfio_group_set_container",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int vfio_group_set_container(struct vfio_group * group, int container_fd)
```

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1359",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421872,
      "name": "vfio_group_set_container",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
    },
    {
      "addr": 18446744071592548180,
      "name": "vfio_group_set_container.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_group_set_container(struct vfio_group * group, int container_fd)
```

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:978",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816496,
      "name": "vfio_group_set_container",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071594427349,
      "name": "vfio_group_set_container.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293367312,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1369",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586693588,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1369",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587000228,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1369",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_set_container",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587107396,
      "name": "vfio_group_set_container",
      "external": false,
      "loc": "drivers/vfio/vfio.c:1369",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int vfio_group_set_container(struct vfio_group * group, int container_fd)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_group_set_container(struct vfio_group * group, int container_fd)
```
</details>
</li>
</ul>
