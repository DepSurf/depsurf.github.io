# Function: <code>vfio_group_release</code>

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
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587038232,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:400",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_put"
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
void vfio_group_release(struct kref * kref)
```

```json
{
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587870832,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:401",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587870832,
      "name": "vfio_group_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void vfio_group_release(struct kref * kref)
```

```json
{
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587931264,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:401",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_device_put",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587931264,
      "name": "vfio_group_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void vfio_group_release(struct kref * kref)
```

```json
{
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587814576,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:391",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814576,
      "name": "vfio_group_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void vfio_group_release(struct kref * kref)
```

```json
{
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418288,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:464",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_unregister_notifier",
        "drivers/vfio/vfio.c:vfio_register_notifier",
        "drivers/vfio/vfio.c:vfio_unpin_pages",
        "drivers/vfio/vfio.c:vfio_pin_pages",
        "drivers/vfio/vfio.c:vfio_group_put_external_user",
        "drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev",
        "drivers/vfio/vfio.c:vfio_group_fops_release",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/vfio/vfio.c:vfio_device_get_from_dev",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put_bg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418288,
      "name": "vfio_group_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void vfio_group_release(struct device * dev)
```

```json
{
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815104,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:330",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815104,
      "name": "vfio_group_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293363164,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:400",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_put"
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
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586686152,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:400",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_put"
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
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586992792,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:400",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_put"
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
  "name": "vfio_group_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587099960,
      "name": "vfio_group_release",
      "external": false,
      "loc": "drivers/vfio/vfio.c:400",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_put"
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
void vfio_group_release(struct kref * kref)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kref * kref</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void vfio_group_release(struct device * dev)
```
</details>
</li>
</ul>
