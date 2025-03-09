# Function: <code>vring_unmap_extra_packed</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vring_unmap_extra_packed(const struct vring_virtqueue * vq, struct vring_desc_extra * extra)
```

```json
{
  "name": "vring_unmap_extra_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588008875,
      "name": "vring_unmap_extra_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:988",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588008816,
      "name": "vring_unmap_extra_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071594296850,
      "name": "vring_unmap_extra_packed.cold",
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
void vring_unmap_extra_packed(const struct vring_virtqueue * vq, struct vring_desc_extra * extra)
```

```json
{
  "name": "vring_unmap_extra_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589380619,
      "name": "vring_unmap_extra_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1173",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380560,
      "name": "vring_unmap_extra_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071596227369,
      "name": "vring_unmap_extra_packed.cold",
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
void vring_unmap_extra_packed(const struct vring_virtqueue * vq, const struct vring_desc_extra * extra)
```

```json
{
  "name": "vring_unmap_extra_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589679390,
      "name": "vring_unmap_extra_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1193",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589679328,
      "name": "vring_unmap_extra_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071596755037,
      "name": "vring_unmap_extra_packed.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void vring_unmap_extra_packed(const struct vring_virtqueue * vq, const struct vring_desc_extra * extra)
```

```json
{
  "name": "vring_unmap_extra_packed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vring_unmap_extra_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1223",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590010128,
      "name": "vring_unmap_extra_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071597663016,
      "name": "vring_unmap_extra_packed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void vring_unmap_extra_packed(const struct vring_virtqueue * vq, struct vring_desc_extra * extra)
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
<code>struct vring_desc_extra * extra</code> ➡️ <code>const struct vring_desc_extra * extra</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
