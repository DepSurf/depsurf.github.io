# Function: <code>alloc_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * alloc_file(struct path * path, fmode_t mode, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000272,
      "name": "alloc_file",
      "external": true,
      "loc": "fs/file_table.c:159",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:SyS_io_setup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:do_shmat",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000272,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct file * alloc_file(struct path * path, fmode_t mode, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158528,
      "name": "alloc_file",
      "external": true,
      "loc": "fs/file_table.c:159",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:do_shmat",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158528,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct file * alloc_file(const struct path * path, fmode_t mode, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235248,
      "name": "alloc_file",
      "external": true,
      "loc": "fs/file_table.c:159",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:do_shmat",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235248,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct file * alloc_file(const struct path * path, fmode_t mode, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282416,
      "name": "alloc_file",
      "external": true,
      "loc": "fs/file_table.c:160",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:do_shmat",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282416,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct file * alloc_file(const struct path * path, fmode_t mode, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421936,
      "name": "alloc_file",
      "external": true,
      "loc": "fs/file_table.c:160",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:do_shmat",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421936,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct file * alloc_file(const struct path * path, fmode_t mode, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579776,
      "name": "alloc_file",
      "external": true,
      "loc": "fs/file_table.c:159",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:do_shmat",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579776,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666288,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:188",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666288,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783408,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783408,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855632,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855632,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079760,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079760,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126144,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:188",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126144,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151728,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:187",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151728,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467840,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:188",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467840,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989072,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:224",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989072,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583549792,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:224",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549792,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583766000,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:288",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766000,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968704,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:285",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968704,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493324144,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493324144,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226920316,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226920316,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286863968,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286863968,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273056870,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273056870,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824368,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824368,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762032,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762032,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815680,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815680,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct file * alloc_file(const struct path * path, int flags, const struct file_operations * fop)
```

```json
{
  "name": "alloc_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884880,
      "name": "alloc_file",
      "external": false,
      "loc": "fs/file_table.c:189",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_clone",
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884880,
      "name": "alloc_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
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
