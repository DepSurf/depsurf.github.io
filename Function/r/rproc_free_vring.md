# Function: <code>rproc_free_vring</code>

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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588235024,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:400",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588235024,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589108778,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:406",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589113104,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589109056,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:406",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589109056,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588998480,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:409",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588998480,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589712720,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:411",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712720,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591220320,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:411",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591220320,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592971984,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:410",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592971984,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593422368,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:410",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593422368,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594168320,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:410",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe",
        "drivers/remoteproc/remoteproc_virtio.c:rp_find_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594168320,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501692568,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:400",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501692568,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234217608,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:400",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234217608,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295127792,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:400",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295127792,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587846720,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:400",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846720,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rproc_free_vring(struct rproc_vring * rvring)
```

```json
{
  "name": "rproc_free_vring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588307360,
      "name": "rproc_free_vring",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:400",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_vdev_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307360,
      "name": "rproc_free_vring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rproc_free_vring(struct rproc_vring * rvring)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
void rproc_free_vring(struct rproc_vring * rvring)
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
void rproc_free_vring(struct rproc_vring * rvring)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void rproc_free_vring(struct rproc_vring * rvring)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
