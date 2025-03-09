# Struct: <code>virtio_blk_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct virtio_blk_config {
    __u64 capacity;
    __u32 size_max;
    __u32 seg_max;
    struct virtio_blk_geometry geometry;
    __u32 blk_size;
    __u8 physical_block_exp;
    __u8 alignment_offset;
    __u16 min_io_size;
    __u32 opt_io_size;
    __u8 wce;
    __u8 unused;
    __u16 num_queues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct virtio_blk_config {
    __u64 capacity;
    __u32 size_max;
    __u32 seg_max;
    struct virtio_blk_geometry geometry;
    __u32 blk_size;
    __u8 physical_block_exp;
    __u8 alignment_offset;
    __u16 min_io_size;
    __u32 opt_io_size;
    __u8 wce;
    __u8 unused;
    __u16 num_queues;
}
```
</details>
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
struct virtio_blk_config {
    __virtio64 capacity;
    __virtio32 size_max;
    __virtio32 seg_max;
    struct virtio_blk_geometry geometry;
    __virtio32 blk_size;
    __u8 physical_block_exp;
    __u8 alignment_offset;
    __virtio16 min_io_size;
    __virtio32 opt_io_size;
    __u8 wce;
    __u8 unused;
    __virtio16 num_queues;
    __virtio32 max_discard_sectors;
    __virtio32 max_discard_seg;
    __virtio32 discard_sector_alignment;
    __virtio32 max_write_zeroes_sectors;
    __virtio32 max_write_zeroes_seg;
    __u8 write_zeroes_may_unmap;
    __u8[3] unused1;
    __virtio32 max_secure_erase_sectors;
    __virtio32 max_secure_erase_seg;
    __virtio32 secure_erase_sector_alignment;
    struct virtio_blk_zoned_characteristics zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct virtio_blk_config {
    __virtio64 capacity;
    __virtio32 size_max;
    __virtio32 seg_max;
    struct virtio_blk_geometry geometry;
    __virtio32 blk_size;
    __u8 physical_block_exp;
    __u8 alignment_offset;
    __virtio16 min_io_size;
    __virtio32 opt_io_size;
    __u8 wce;
    __u8 unused;
    __virtio16 num_queues;
    __virtio32 max_discard_sectors;
    __virtio32 max_discard_seg;
    __virtio32 discard_sector_alignment;
    __virtio32 max_write_zeroes_sectors;
    __virtio32 max_write_zeroes_seg;
    __u8 write_zeroes_may_unmap;
    __u8[3] unused1;
    __virtio32 max_secure_erase_sectors;
    __virtio32 max_secure_erase_seg;
    __virtio32 secure_erase_sector_alignment;
    struct virtio_blk_zoned_characteristics zoned;
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct virtio_blk_config {
    __u64 capacity;
    __u32 size_max;
    __u32 seg_max;
    struct virtio_blk_geometry geometry;
    __u32 blk_size;
    __u8 physical_block_exp;
    __u8 alignment_offset;
    __u16 min_io_size;
    __u32 opt_io_size;
    __u8 wce;
    __u8 unused;
    __u16 num_queues;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct virtio_blk_config {
    __virtio64 capacity;
    __virtio32 size_max;
    __virtio32 seg_max;
    struct virtio_blk_geometry geometry;
    __virtio32 blk_size;
    __u8 physical_block_exp;
    __u8 alignment_offset;
    __virtio16 min_io_size;
    __virtio32 opt_io_size;
    __u8 wce;
    __u8 unused;
    __virtio16 num_queues;
    __virtio32 max_discard_sectors;
    __virtio32 max_discard_seg;
    __virtio32 discard_sector_alignment;
    __virtio32 max_write_zeroes_sectors;
    __virtio32 max_write_zeroes_seg;
    __u8 write_zeroes_may_unmap;
    __u8[3] unused1;
    __virtio32 max_secure_erase_sectors;
    __virtio32 max_secure_erase_seg;
    __virtio32 secure_erase_sector_alignment;
    struct virtio_blk_zoned_characteristics zoned;
}
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
