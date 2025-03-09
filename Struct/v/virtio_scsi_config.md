# Struct: <code>virtio_scsi_config</code>

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
struct virtio_scsi_config {
    __virtio32 num_queues;
    __virtio32 seg_max;
    __virtio32 max_sectors;
    __virtio32 cmd_per_lun;
    __virtio32 event_info_size;
    __virtio32 sense_size;
    __virtio32 cdb_size;
    __virtio16 max_channel;
    __virtio16 max_target;
    __virtio32 max_lun;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct virtio_scsi_config {
    __virtio32 num_queues;
    __virtio32 seg_max;
    __virtio32 max_sectors;
    __virtio32 cmd_per_lun;
    __virtio32 event_info_size;
    __virtio32 sense_size;
    __virtio32 cdb_size;
    __virtio16 max_channel;
    __virtio16 max_target;
    __virtio32 max_lun;
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
struct virtio_scsi_config {
    __u32 num_queues;
    __u32 seg_max;
    __u32 max_sectors;
    __u32 cmd_per_lun;
    __u32 event_info_size;
    __u32 sense_size;
    __u32 cdb_size;
    __u16 max_channel;
    __u16 max_target;
    __u32 max_lun;
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
struct virtio_scsi_config {
    __virtio32 num_queues;
    __virtio32 seg_max;
    __virtio32 max_sectors;
    __virtio32 cmd_per_lun;
    __virtio32 event_info_size;
    __virtio32 sense_size;
    __virtio32 cdb_size;
    __virtio16 max_channel;
    __virtio16 max_target;
    __virtio32 max_lun;
}
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
struct virtio_scsi_config {
    __u32 num_queues;
    __u32 seg_max;
    __u32 max_sectors;
    __u32 cmd_per_lun;
    __u32 event_info_size;
    __u32 sense_size;
    __u32 cdb_size;
    __u16 max_channel;
    __u16 max_target;
    __u32 max_lun;
}
```
</details>
</li>
</ul>
