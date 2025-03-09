# Function: <code>vring_alloc_state_extra_split</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int vring_alloc_state_extra_split(struct vring_virtqueue_split * vring_split)
```

```json
{
  "name": "vring_alloc_state_extra_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589389296,
      "name": "vring_alloc_state_extra_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1008",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_resize",
        "drivers/virtio/virtio_ring.c:__vring_new_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389296,
      "name": "vring_alloc_state_extra_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int vring_alloc_state_extra_split(struct vring_virtqueue_split * vring_split)
```

```json
{
  "name": "vring_alloc_state_extra_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688128,
      "name": "vring_alloc_state_extra_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1022",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_resize",
        "drivers/virtio/virtio_ring.c:__vring_new_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688128,
      "name": "vring_alloc_state_extra_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int vring_alloc_state_extra_split(struct vring_virtqueue_split * vring_split)
```

```json
{
  "name": "vring_alloc_state_extra_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590021936,
      "name": "vring_alloc_state_extra_split",
      "external": false,
      "loc": "drivers/virtio/virtio_ring.c:1052",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:__vring_new_virtqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590021936,
      "name": "vring_alloc_state_extra_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int vring_alloc_state_extra_split(struct vring_virtqueue_split * vring_split)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
