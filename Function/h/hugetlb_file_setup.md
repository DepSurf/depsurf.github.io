# Function: <code>hugetlb_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945776,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1235",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945776,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157232,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1241",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157232,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246640,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1239",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246640,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331600,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1300",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331600,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482160,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1300",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:SyS_memfd_create",
        "mm/mmap.c:SyS_mmap_pgoff",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482160,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1321",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674100,
      "name": "hugetlb_file_setup.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582673200,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1327",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775972,
      "name": "hugetlb_file_setup.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582775232,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950045,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582949376,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056701,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583056032,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1453",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375741,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583375072,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1454",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591352121,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583491104,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1448",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295036,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583513184,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct ucounts * * ucounts, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1449",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592277880,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071583868544,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1500",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594060110,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071584441920,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1576",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596088418,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585104192,
      "name": "hugetlb_file_setup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1571",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596611831,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585333440,
      "name": "hugetlb_file_setup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1593",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__do_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597517785,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585568112,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494754040,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__arm64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494754040,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": false,
      "loc": "include/linux/hugetlb.h:306",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": false,
      "loc": "include/linux/hugetlb.h:306",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": false,
      "loc": "include/linux/hugetlb.h:306",
      "file": "ipc/shm.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288584768,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__se_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288584768,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274097210,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__se_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274097210,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025437,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583024768,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962589,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582961920,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014045,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583013376,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```

```json
{
  "name": "hugetlb_file_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_file_setup",
      "external": true,
      "loc": "fs/hugetlbfs/inode.c:1367",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103211,
      "name": "hugetlb_file_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583102544,
      "name": "hugetlb_file_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucounts * * ucounts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_struct * * user</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ucounts * * ucounts</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, size, acctflag, ucounts, creat_flags, page_size_log</code> ➡️ <code>name, size, acctflag, creat_flags, page_size_log</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct file * hugetlb_file_setup(const char * name, size_t size, vm_flags_t acctflag, struct user_struct * * user, int creat_flags, int page_size_log)
```
</details>
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
