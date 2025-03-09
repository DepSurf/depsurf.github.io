# Function: <code>virtio_reset_device</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_reset_device(struct virtio_device * dev)
```

```json
{
  "name": "virtio_reset_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588006364,
      "name": "virtio_reset_device",
      "external": true,
      "loc": "drivers/virtio/virtio.c:220",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_restore",
        "drivers/virtio/virtio.c:register_virtio_device"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/iommu/virtio-iommu.c:viommu_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588004432,
      "name": "virtio_reset_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_reset_device(struct virtio_device * dev)
```

```json
{
  "name": "virtio_reset_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589377788,
      "name": "virtio_reset_device",
      "external": true,
      "loc": "drivers/virtio/virtio.c:220",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_restore",
        "drivers/virtio/virtio.c:register_virtio_device"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/iommu/virtio-iommu.c:viommu_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375504,
      "name": "virtio_reset_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_reset_device(struct virtio_device * dev)
```

```json
{
  "name": "virtio_reset_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589676428,
      "name": "virtio_reset_device",
      "external": true,
      "loc": "drivers/virtio/virtio.c:220",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_restore",
        "drivers/virtio/virtio.c:register_virtio_device"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/iommu/virtio-iommu.c:viommu_remove",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_freeze",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_init",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674144,
      "name": "virtio_reset_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_reset_device(struct virtio_device * dev)
```

```json
{
  "name": "virtio_reset_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590007340,
      "name": "virtio_reset_device",
      "external": true,
      "loc": "drivers/virtio/virtio.c:220",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_restore",
        "drivers/virtio/virtio.c:register_virtio_device"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/iommu/virtio-iommu.c:viommu_remove",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_freeze",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_init",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590004992,
      "name": "virtio_reset_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void virtio_reset_device(struct virtio_device * dev)
```
</details>
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
