# Function: <code>do_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710016,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1267",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:SyS_remap_file_pages",
        "fs/aio.c:SyS_io_setup",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710016,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1041
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580826160,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1151",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:SyS_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826160,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1290
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891664,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1304",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:SyS_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891664,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1314
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936720,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1320",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:SyS_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936720,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1150
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036496,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1321",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:SyS_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036496,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1201
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171664,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1359",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171664,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1434
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252016,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1383",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252016,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1397
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326896,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1385",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326896,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1407
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386240,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386240,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1459
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582256,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1366",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582256,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1464
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628128,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1404",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628128,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1489
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651936,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1408",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651936,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919968,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1404",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919968,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1407
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326464,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1416",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326464,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582826096,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1239",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582826096,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1441
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583041424,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1188",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041424,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1495
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583223248,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1216",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/shstk.c:alloc_shstk",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583223248,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492792216,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492792216,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226607820,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226607820,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286162736,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286162736,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1520
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272761788,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272761788,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581355088,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355088,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1459
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298800,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298800,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1459
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346288,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346288,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1459
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
long unsigned int do_mmap(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int * populate, struct list_head * uf)
```

```json
{
  "name": "do_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410224,
      "name": "do_mmap",
      "external": true,
      "loc": "mm/mmap.c:1389",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "fs/aio.c:aio_setup_ring",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410224,
      "name": "do_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1459
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head * uf</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>vm_flags_t vm_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, addr, len, prot, flags, vm_flags, pgoff, populate, uf</code> ➡️ <code>file, addr, len, prot, flags, pgoff, populate, uf</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>vm_flags_t vm_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, addr, len, prot, flags, pgoff, populate, uf</code> ➡️ <code>file, addr, len, prot, flags, vm_flags, pgoff, populate, uf</code>
</li>
</ul>
</details>
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
