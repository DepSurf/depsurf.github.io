# Function: <code>flush_dcache_page</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:38",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590937562,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591001783,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590921391,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591770422,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593488705,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595407251,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595804780,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596655363,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:51",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void flush_dcache_page(struct page * page)
```

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490343336,
      "name": "flush_dcache_page",
      "external": true,
      "loc": "arch/arm64/mm/flush.c:68",
      "file": "arch/arm64/mm/flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages",
        "arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages",
        "arch/arm64/mm/copypage.c:__cpu_copy_user_page",
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_insert_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/migrate.c:move_to_new_page",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:__block_write_begin_int",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_setup_ring",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate",
        "block/bio.c:zero_fill_bio_iter",
        "block/blk-core.c:rq_flush_dcache_pages",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_set_status",
        "net/packet/af_packet.c:__packet_set_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490343336,
      "name": "flush_dcache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void flush_dcache_page(struct page * page)
```

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224497108,
      "name": "flush_dcache_page",
      "external": true,
      "loc": "arch/arm/mm/flush.c:315",
      "file": "arch/arm/mm/flush.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/vdso.c:update_vsyscall_tz",
        "arch/arm/kernel/vdso.c:update_vsyscall",
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_page",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/migrate.c:move_to_new_page",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage",
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:__block_write_begin_int",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_setup_ring",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate",
        "block/bio.c:zero_fill_bio_iter",
        "block/blk-core.c:rq_flush_dcache_pages",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:copy_to_high_bio_irq",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224497108,
      "name": "flush_dcache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void flush_dcache_page(struct page * page)
```

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282718068,
      "name": "flush_dcache_page",
      "external": true,
      "loc": "arch/powerpc/mm/mem.c:472",
      "file": "arch/powerpc/mm/mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/mem.c:copy_user_page",
        "arch/powerpc/mm/mem.c:clear_user_page"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_insert_page",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/migrate.c:move_to_new_page",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:__block_write_begin_int",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_setup_ring",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate",
        "block/bio.c:zero_fill_bio_iter",
        "block/blk-core.c:rq_flush_dcache_pages",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_current_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282716832,
      "name": "flush_dcache_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272518868,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272585422,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272636038,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272715152,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272721214,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272912294,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272954654,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:move_to_new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273046670,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273223886,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273305948,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_write_end",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273325514,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273332090,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273389580,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273519758,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273764198,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273786018,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273864134,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273896896,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273898808,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273966946,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274074362,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274081636,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274082958,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274157602,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274159004,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274204560,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274240190,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274917948,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate",
        "block/bio.c:zero_fill_bio_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276504640,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276941706,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279581988,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:77",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_get_status",
        "net/packet/af_packet.c:__packet_set_status"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/nvdimm/btt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_dcache_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_dcache_page",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:49",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void flush_dcache_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void flush_dcache_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void flush_dcache_page(struct page * page)
```
</details>
</li>
</ul>
