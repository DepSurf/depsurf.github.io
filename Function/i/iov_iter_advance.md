# Function: <code>iov_iter_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583019664,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:509",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_direct_write",
        "fs/read_write.c:do_loop_readv_writev",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019664,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583314640,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:458",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:do_loop_readv_writev",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314640,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583435472,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:779",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:do_loop_readv_writev",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:copy_from_iter_full_nocache",
        "lib/iov_iter.c:copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583435472,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 915
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583456960,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:841",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456960,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583637440,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:843",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637440,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853648,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:973",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853648,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938464,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1019",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_bio_actor",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938464,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116944,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116944,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240096,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240096,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584655424,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1065",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/io_uring.c:io_import_fixed",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655424,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584767216,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1072",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/io_uring.c:loop_rw_iter",
        "fs/io_uring.c:io_import_fixed",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767216,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815312,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1158",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/io_uring.c:loop_rw_iter",
        "fs/io_uring.c:io_import_iovec",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_fill_write_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815312,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1019",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:loop_rw_iter",
        "fs/io_uring.c:io_import_iovec",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323284,
      "name": "iov_iter_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585224656,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1071",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:loop_rw_iter",
        "io_uring/io_uring.c:__io_import_iovec",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127110,
      "name": "iov_iter_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586063232,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587045824,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:895",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/rsrc.c:io_import_fixed",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:loop_rw_iter",
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045824,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587297808,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:629",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:loop_rw_iter",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297808,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587583616,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:530",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:loop_rw_iter",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "lib/iov_iter.c:iov_iter_extract_pages",
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/packet/af_packet.c:packet_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583616,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496117256,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496117256,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229441984,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/io_uring.c:io_import_iovec",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229441984,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290369072,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290369072,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275180150,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275180150,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
    }
  ]
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
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208832,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208832,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144048,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144048,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192592,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192592,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter * i, size_t size)
```

```json
{
  "name": "iov_iter_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584297056,
      "name": "iov_iter_advance",
      "external": true,
      "loc": "lib/iov_iter.c:1033",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/direct-io.c:do_direct_IO",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_iov_iter_get_pages",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "drivers/char/mem.c:write_iter_null",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297056,
      "name": "iov_iter_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
    }
  ]
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
