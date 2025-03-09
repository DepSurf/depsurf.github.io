# Function: <code>vp_modern_set_queue_enable</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```

```json
{
  "name": "vp_modern_set_queue_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237968,
      "name": "vp_modern_set_queue_enable",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:516",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237968,
      "name": "vp_modern_set_queue_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```

```json
{
  "name": "vp_modern_set_queue_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586746928,
      "name": "vp_modern_set_queue_enable",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:537",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586746928,
      "name": "vp_modern_set_queue_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```

```json
{
  "name": "vp_modern_set_queue_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588022320,
      "name": "vp_modern_set_queue_enable",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:548",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022320,
      "name": "vp_modern_set_queue_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```

```json
{
  "name": "vp_modern_set_queue_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397536,
      "name": "vp_modern_set_queue_enable",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:587",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_modern_enable_vq_after_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397536,
      "name": "vp_modern_set_queue_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```

```json
{
  "name": "vp_modern_set_queue_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589696624,
      "name": "vp_modern_set_queue_enable",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:596",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_modern_enable_vq_after_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589696624,
      "name": "vp_modern_set_queue_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```

```json
{
  "name": "vp_modern_set_queue_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590029392,
      "name": "vp_modern_set_queue_enable",
      "external": true,
      "loc": "drivers/virtio/virtio_pci_modern_dev.c:605",
      "file": "drivers/virtio/virtio_pci_modern_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_modern_create_avq",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_enable_vq_after_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590029392,
      "name": "vp_modern_set_queue_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void vp_modern_set_queue_enable(struct virtio_pci_modern_device * mdev, u16 index, bool enable)
```
</details>
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
