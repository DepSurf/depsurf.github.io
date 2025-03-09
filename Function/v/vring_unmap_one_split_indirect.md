# Function: <code>vring_unmap_one_split_indirect</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_one_split_indirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586737564,
      "name": "vring_unmap_one_split_indirect",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:372",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737008,
      "name": "vring_unmap_one_split_indirect.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue * vq, struct vring_desc * desc)
```

```json
{
  "name": "vring_unmap_one_split_indirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588010985,
      "name": "vring_unmap_one_split_indirect",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:372",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010944,
      "name": "vring_unmap_one_split_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071594297502,
      "name": "vring_unmap_one_split_indirect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue * vq, struct vring_desc * desc)
```

```json
{
  "name": "vring_unmap_one_split_indirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589381993,
      "name": "vring_unmap_one_split_indirect",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:419",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381952,
      "name": "vring_unmap_one_split_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071596227577,
      "name": "vring_unmap_one_split_indirect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue * vq, const struct vring_desc * desc)
```

```json
{
  "name": "vring_unmap_one_split_indirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589680233,
      "name": "vring_unmap_one_split_indirect",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:425",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680192,
      "name": "vring_unmap_one_split_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071596755169,
      "name": "vring_unmap_one_split_indirect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue * vq, const struct vring_desc * desc)
```

```json
{
  "name": "vring_unmap_one_split_indirect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590012105,
      "name": "vring_unmap_one_split_indirect",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:443",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012064,
      "name": "vring_unmap_one_split_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071597663459,
      "name": "vring_unmap_one_split_indirect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue * vq, struct vring_desc * desc)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vring_desc * desc</code> ➡️ <code>const struct vring_desc * desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
