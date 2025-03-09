# Function: <code>virtscsi_kick_event</code>

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
  "name": "virtscsi_kick_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591305392,
      "name": "virtscsi_kick_event",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:229",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_restore",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591305392,
      "name": "virtscsi_kick_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtscsi_kick_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591653840,
      "name": "virtscsi_kick_event",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:233",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_restore",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591653840,
      "name": "virtscsi_kick_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int virtscsi_kick_event(struct virtio_scsi * vscsi, struct virtio_scsi_event_node * event_node)
```

```json
{
  "name": "virtscsi_kick_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586650672,
      "name": "virtscsi_kick_event",
      "external": false,
      "loc": "drivers/scsi/virtio_scsi.c:230",
      "file": "drivers/scsi/virtio_scsi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/virtio_scsi.c:virtscsi_restore",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650672,
      "name": "virtscsi_kick_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int virtscsi_kick_event(struct virtio_scsi * vscsi, struct virtio_scsi_event_node * event_node)
```
</details>
</li>
</ul>
