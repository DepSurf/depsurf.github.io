# Function: <code>copy_page_to_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583030192,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:449",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "block/bio.c:bio_uncopy_user",
        "net/core/datagram.c:skb_copy_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030192,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583321328,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:404",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "block/bio.c:bio_uncopy_user",
        "net/core/datagram.c:skb_copy_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321328,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583446352,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:642",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/core/datagram.c:skb_copy_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446352,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583462560,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:697",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/core/datagram.c:skb_copy_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462560,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583643040,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:699",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/core/datagram.c:skb_copy_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643040,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583861184,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:829",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/core/datagram.c:skb_copy_datagram_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861184,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583944800,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:873",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944800,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584127240,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132664,
      "name": "copy_page_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071584126864,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584246704,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246704,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659760,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:908",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/process_vm_access.c:process_vm_rw_single_vec",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_to_iter",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659760,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773296,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:915",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_to_iter",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773296,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814000,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:979",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:blk_rq_unmap_user",
        "net/core/skmsg.c:sk_msg_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814000,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:826",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:blk_rq_unmap_user",
        "net/core/skmsg.c:sk_msg_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323440,
      "name": "copy_page_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585238688,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1009
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586077584,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:878",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:blk_rq_unmap_user",
        "net/core/skmsg.c:sk_msg_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077584,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:712",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:blk_rq_unmap_user",
        "net/core/skmsg.c:sk_msg_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596114429,
      "name": "copy_page_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587054256,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587306753,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:468",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:blk_rq_unmap_user",
        "net/core/skmsg.c:sk_msg_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596639554,
      "name": "copy_page_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587306672,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587597041,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:349",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:blk_rq_unmap_user",
        "net/core/skmsg.c:sk_msg_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548256,
      "name": "copy_page_to_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071587596960,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496124624,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496124624,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229447940,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229447940,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290376656,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290376656,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275184842,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275184842,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584215440,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215440,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584150656,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150656,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584199200,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199200,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_to_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584303696,
      "name": "copy_page_to_iter",
      "external": true,
      "loc": "lib/iov_iter.c:887",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_buffered_read",
        "mm/shmem.c:shmem_file_read_iter",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:pipe_to_user",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_uncopy_user",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303696,
      "name": "copy_page_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
