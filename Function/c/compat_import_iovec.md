# Function: <code>compat_import_iovec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030352,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:819",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/aio.c:aio_run_iocb",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030352,
      "name": "compat_import_iovec",
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
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322944,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:775",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/aio.c:aio_run_iocb",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322944,
      "name": "compat_import_iovec",
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
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447856,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1289",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447856,
      "name": "compat_import_iovec",
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
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468512,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1413",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468512,
      "name": "compat_import_iovec",
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
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649424,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1415",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649424,
      "name": "compat_import_iovec",
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
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867232,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1545",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867232,
      "name": "compat_import_iovec",
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
int compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952560,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1641",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952560,
      "name": "compat_import_iovec",
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
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131888,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131888,
      "name": "compat_import_iovec",
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
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254784,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254784,
      "name": "compat_import_iovec",
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
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644944,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1697",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644944,
      "name": "compat_import_iovec",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496133320,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496133320,
      "name": "compat_import_iovec",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290390464,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290390464,
      "name": "compat_import_iovec",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223520,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223520,
      "name": "compat_import_iovec",
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
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584158736,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158736,
      "name": "compat_import_iovec",
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
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207280,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207280,
      "name": "compat_import_iovec",
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
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```

```json
{
  "name": "compat_import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584311840,
      "name": "compat_import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_readv",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/aio.c:aio_setup_rw",
        "security/keys/compat.c:compat_keyctl_instantiate_key_iov",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311840,
      "name": "compat_import_iovec",
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
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t compat_import_iovec(int type, const struct compat_iovec * uvector, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iov, struct iov_iter * i)
```
</details>
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
