# Function: <code>virtscsi_add_cmd</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int virtscsi_add_cmd(struct virtio_scsi_vq * vq, struct virtio_scsi_cmd * cmd, size_t req_size, size_t resp_size, bool kick)
```

```json
{
  "name": "virtscsi_add_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591305216,
      "name": "virtscsi_add_cmd",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:491",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_queuecommand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591305216,
      "name": "virtscsi_add_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int virtscsi_add_cmd(struct virtio_scsi_vq * vq, struct virtio_scsi_cmd * cmd, size_t req_size, size_t resp_size, bool kick)
```

```json
{
  "name": "virtscsi_add_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591653664,
      "name": "virtscsi_add_cmd",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:495",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_queuecommand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591653664,
      "name": "virtscsi_add_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int virtscsi_add_cmd(struct virtio_scsi_vq * vq, struct virtio_scsi_cmd * cmd, size_t req_size, size_t resp_size, bool kick)
```

```json
{
  "name": "virtscsi_add_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651744,
      "name": "virtscsi_add_cmd",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:471",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_queuecommand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651744,
      "name": "virtscsi_add_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int virtscsi_add_cmd(struct virtio_scsi_vq * vq, struct virtio_scsi_cmd * cmd, size_t req_size, size_t resp_size, bool kick)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➕</summary>

```c
int virtscsi_add_cmd(struct virtio_scsi_vq * vq, struct virtio_scsi_cmd * cmd, size_t req_size, size_t resp_size, bool kick)
```
</details>
</li>
</ul>
