# Function: <code>vfio_device_get_from_name</code>

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
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587046102,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:875",
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
struct vfio_device * vfio_device_get_from_name(struct vfio_group * group, char * buf)
```

```json
{
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875792,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:878",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875792,
      "name": "vfio_device_get_from_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct vfio_device * vfio_device_get_from_name(struct vfio_group * group, char * buf)
```

```json
{
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587936256,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:879",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936256,
      "name": "vfio_device_get_from_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587813551,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:824",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588417273,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:910",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589820860,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:630",
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
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293367732,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:875",
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
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586694022,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:875",
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
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587000662,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:875",
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
  "name": "vfio_device_get_from_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587107830,
      "name": "vfio_device_get_from_name",
      "external": false,
      "loc": "drivers/vfio/vfio.c:875",
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
struct vfio_device * vfio_device_get_from_name(struct vfio_group * group, char * buf)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct vfio_device * vfio_device_get_from_name(struct vfio_group * group, char * buf)
```
</details>
</li>
</ul>
