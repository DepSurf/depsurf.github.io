# Struct: <code>queue_limits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char cluster;
    unsigned char discard_zeroes_data;
    unsigned char raid_partial_stripes_expensive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char cluster;
    unsigned char discard_zeroes_data;
    unsigned char raid_partial_stripes_expensive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char cluster;
    unsigned char discard_zeroes_data;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char cluster;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char cluster;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char cluster;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int logical_block_size;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    enum blk_bounce bounce;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int zone_write_granularity;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    enum blk_bounce bounce;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int zone_write_granularity;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    enum blk_bounce bounce;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_secure_erase_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int zone_write_granularity;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    enum blk_bounce bounce;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_secure_erase_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int zone_write_granularity;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
    unsigned int dma_alignment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    enum blk_bounce bounce;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_user_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_secure_erase_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int zone_write_granularity;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
    unsigned int dma_alignment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct queue_limits {
    enum blk_bounce bounce;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_user_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_secure_erase_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int max_zone_append_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int zone_write_granularity;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    bool zoned;
    unsigned int dma_alignment;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct queue_limits {
    long unsigned int bounce_pfn;
    long unsigned int seg_boundary_mask;
    long unsigned int virt_boundary_mask;
    unsigned int max_hw_sectors;
    unsigned int max_dev_sectors;
    unsigned int chunk_sectors;
    unsigned int max_sectors;
    unsigned int max_segment_size;
    unsigned int physical_block_size;
    unsigned int logical_block_size;
    unsigned int alignment_offset;
    unsigned int io_min;
    unsigned int io_opt;
    unsigned int max_discard_sectors;
    unsigned int max_hw_discard_sectors;
    unsigned int max_write_same_sectors;
    unsigned int max_write_zeroes_sectors;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    short unsigned int max_segments;
    short unsigned int max_integrity_segments;
    short unsigned int max_discard_segments;
    unsigned char misaligned;
    unsigned char discard_misaligned;
    unsigned char raid_partial_stripes_expensive;
    enum blk_zoned_model zoned;
}
```
</details>
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
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int max_write_zeroes_sectors</code>
</li>
<li>
<b>Field added. </b>
<code>enum blk_zoned_model zoned</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>short unsigned int max_discard_segments</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char discard_zeroes_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned char cluster</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>short unsigned int logical_block_size</code> ➡️ <code>unsigned int logical_block_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int max_zone_append_sectors</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum blk_bounce bounce</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zone_write_granularity</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int bounce_pfn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int max_secure_erase_sectors</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int max_write_same_sectors</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int dma_alignment</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int max_user_sectors</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>enum blk_zoned_model zoned</code> ➡️ <code>bool zoned</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
