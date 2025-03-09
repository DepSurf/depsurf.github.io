# Function: <code>alloc_file_pseudo</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666528,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:214",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666528,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783648,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783648,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855872,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855872,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080032,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:216",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080032,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126416,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126416,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152000,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:214",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152000,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468112,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468112,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989344,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:251",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989344,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583550160,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:254",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583550160,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583766384,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:318",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766384,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969088,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:315",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/anon_inodes.c:__anon_inode_getfile",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969088,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493324440,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493324440,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226920592,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226920592,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286864304,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286864304,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273057074,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273057074,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824608,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824608,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762272,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762272,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815920,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815920,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```

```json
{
  "name": "alloc_file_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885120,
      "name": "alloc_file_pseudo",
      "external": true,
      "loc": "fs/file_table.c:215",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885120,
      "name": "alloc_file_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct file * alloc_file_pseudo(struct inode * inode, struct vfsmount * mnt, const char * name, int flags, const struct file_operations * fops)
```
</details>
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
