# Function: <code>compat_rw_copy_check_uvector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354320,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/compat.c:546",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354320,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535360,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/compat.c:546",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535360,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620960,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/compat.c:493",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620960,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279872,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:823",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279872,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418704,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:828",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418704,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578048,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:855",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578048,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663808,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:852",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663808,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780880,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780880,
      "name": "compat_rw_copy_check_uvector",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853104,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853104,
      "name": "compat_rw_copy_check_uvector",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077712,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:894",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077712,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493320368,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493320368,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286860320,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286860320,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821840,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821840,
      "name": "compat_rw_copy_check_uvector",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759504,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759504,
      "name": "compat_rw_copy_check_uvector",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813152,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813152,
      "name": "compat_rw_copy_check_uvector",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
```

```json
{
  "name": "compat_rw_copy_check_uvector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882368,
      "name": "compat_rw_copy_check_uvector",
      "external": true,
      "loc": "fs/read_write.c:866",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_process_vm_rw",
        "lib/iov_iter.c:compat_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882368,
      "name": "compat_rw_copy_check_uvector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec * uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_pointer, struct iovec * * ret_pointer)
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
