# Function: <code>vring_unmap_state_packed</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585159018,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:910",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585376582,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585517062,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586228371,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586344412,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586228816,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vring_unmap_state_packed(const struct vring_virtqueue * vq, struct vring_desc_extra * state)
```

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735691,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:987",
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
      "addr": 18446744071586735632,
      "name": "vring_unmap_state_packed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071592428919,
      "name": "vring_unmap_state_packed.cold",
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498163624,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230927676,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291406480,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275945722,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585279142,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585231606,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585467462,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
  "name": "vring_unmap_state_packed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585575638,
      "name": "vring_unmap_state_packed",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:914",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:detach_buf_packed"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void vring_unmap_state_packed(const struct vring_virtqueue * vq, struct vring_desc_extra * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void vring_unmap_state_packed(const struct vring_virtqueue * vq, struct vring_desc_extra * state)
```
</details>
</li>
</ul>
