# Function: <code>virtscsi_vq_done</code>

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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtscsi_vq_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591311237,
      "name": "virtscsi_vq_done",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:170",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/virtio_scsi.c:virtscsi_event_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_req_done"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtscsi_vq_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591658005,
      "name": "virtscsi_vq_done",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:176",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/virtio_scsi.c:virtscsi_event_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_req_done"
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
void virtscsi_vq_done(struct virtio_scsi * vscsi, struct virtio_scsi_vq * virtscsi_vq, void (*)(struct virtio_scsi *, void *) fn)
```

```json
{
  "name": "virtscsi_vq_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586650304,
      "name": "virtscsi_vq_done",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:171",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_event_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_req_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650304,
      "name": "virtscsi_vq_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➕</summary>

```c
void virtscsi_vq_done(struct virtio_scsi * vscsi, struct virtio_scsi_vq * virtscsi_vq, void (*)(struct virtio_scsi *, void *) fn)
```
</details>
</li>
</ul>
