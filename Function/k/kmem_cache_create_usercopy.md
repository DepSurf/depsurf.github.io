# Function: <code>kmem_cache_create_usercopy</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:436",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069883,
      "name": "kmem_cache_create_usercopy.cold.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581067328,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:438",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147759,
      "name": "kmem_cache_create_usercopy.cold.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581145120,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:453",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214596,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071581211760,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273209,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581270256,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463270,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581460272,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:302",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591326395,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581498400,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:310",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591268444,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581519600,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:310",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592194948,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581781264,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:302",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593971002,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582168320,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648704,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:278",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_cache_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648704,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582858304,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:278",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_cache_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858304,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583033568,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:273",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_cache_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "io_uring/io_uring.c:io_uring_init",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033568,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492675128,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_init",
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492675128,
      "name": "kmem_cache_create_usercopy",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226513932,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226513932,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286000528,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/fork.c:thread_stack_cache_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286000528,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272682252,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272682252,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242057,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581239104,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188729,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581185776,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233257,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581230304,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```

```json
{
  "name": "kmem_cache_create_usercopy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_create_usercopy",
      "external": true,
      "loc": "mm/slab_common.c:454",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:proc_caches_init",
        "kernel/fork.c:fork_init",
        "kernel/utsname.c:uts_ns_init",
        "mm/slab_common.c:kmem_cache_create",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/verity/open.c:fsverity_init_info_cache",
        "fs/proc/inode.c:proc_init_kmemcache",
        "fs/ext4/super.c:ext4_init_fs",
        "drivers/scsi/scsi_lib.c:scsi_init_sense_cache",
        "net/core/sock.c:proto_register",
        "net/core/skbuff.c:skb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296793,
      "name": "kmem_cache_create_usercopy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581293808,
      "name": "kmem_cache_create_usercopy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct kmem_cache * kmem_cache_create_usercopy(const char * name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor)
```
</details>
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
