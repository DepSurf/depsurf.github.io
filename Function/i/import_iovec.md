# Function: <code>import_iovec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020768,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:796",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:do_readv_writev",
        "fs/splice.c:vmsplice_to_user",
        "fs/aio.c:aio_run_iocb",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020768,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312528,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:752",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:do_readv_writev",
        "fs/splice.c:vmsplice_to_user",
        "fs/aio.c:aio_run_iocb",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312528,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583431840,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1266",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:do_readv_writev",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583431840,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452512,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1390",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452512,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632608,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1392",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:vmsplice_to_user",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632608,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849200,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1522",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849200,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933088,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1618",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933088,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111312,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111312,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234096,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234096,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644704,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1674",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644704,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780192,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1809",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780192,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584824288,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:2097",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584824288,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242448,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1955",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242448,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083360,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:2004",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083360,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587064368,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1856",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "net/socket.c:copy_msghdr_from_user",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064368,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322448,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1515",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "net/socket.c:copy_msghdr_from_user",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322448,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
ssize_t import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587605392,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1340",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "net/socket.c:copy_msghdr_from_user",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587605392,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496109992,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496109992,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229435356,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/io_uring.c:io_import_iovec",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229435356,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290359472,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290359472,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275175210,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275175210,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202832,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202832,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138048,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138048,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186592,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186592,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
ssize_t import_iovec(int type, const struct iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291024,
      "name": "import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1639",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/keyctl.c:keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "net/socket.c:copy_msghdr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291024,
      "name": "import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iovec * uvec</code>
</li>
<li>
<b>Param added. </b>
<code>struct iovec * * iovp</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct iovec * uvector</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iovec * * iov</code>
</li>
</ul>
</details>
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
