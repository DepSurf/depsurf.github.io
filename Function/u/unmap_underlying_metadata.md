# Function: <code>unmap_underlying_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unmap_underlying_metadata(struct block_device * bdev, sector_t block)
```

```json
{
  "name": "unmap_underlying_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221408,
      "name": "unmap_underlying_metadata",
      "external": true,
      "loc": "fs/buffer.c:1634",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221408,
      "name": "unmap_underlying_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void unmap_underlying_metadata(struct block_device * bdev, sector_t block)
```

```json
{
  "name": "unmap_underlying_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385984,
      "name": "unmap_underlying_metadata",
      "external": true,
      "loc": "fs/buffer.c:1624",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385984,
      "name": "unmap_underlying_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
void unmap_underlying_metadata(struct block_device * bdev, sector_t block)
```
</details>
</li>
</ul>
