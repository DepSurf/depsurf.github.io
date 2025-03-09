# Function: <code>rproc_vdev_release</code>

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
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588236128,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:570",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588236128,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589113232,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:577",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589113232,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589111808,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:610",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589111808,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589000251,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:614",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589001616,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589714539,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:618",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589715952,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591222167,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:618",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223808,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501693744,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:570",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501693744,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234218888,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:570",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234218888,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295129248,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:570",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295129248,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587847824,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:570",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847824,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref * ref)
```

```json
{
  "name": "rproc_vdev_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308464,
      "name": "rproc_vdev_release",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:570",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308464,
      "name": "rproc_vdev_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void rproc_vdev_release(struct kref * ref)
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
void rproc_vdev_release(struct kref * ref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rproc_vdev_release(struct kref * ref)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void rproc_vdev_release(struct kref * ref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void rproc_vdev_release(struct kref * ref)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
