# Function: <code>vma_is_shmem</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795168,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:204",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795168,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884992,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:237",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884992,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021344,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:237",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021344,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098960,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:239",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098960,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164192,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:244",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164192,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222112,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222112,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409632,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:258",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409632,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581451792,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:257",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451792,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472736,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:257",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_active",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472736,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715920,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:253",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_active",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715920,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105488,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:251",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_active",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "io_uring/io_uring.c:io_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105488,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579472,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:248",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "io_uring/rsrc.c:io_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579472,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786672,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:249",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786672,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582962160,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:271",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962160,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492607784,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492607784,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226462420,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226462420,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285926256,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285926256,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272637498,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272637498,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190960,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190960,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137712,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137712,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182160,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182160,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool vma_is_shmem(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_is_shmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581245392,
      "name": "vma_is_shmem",
      "external": true,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245392,
      "name": "vma_is_shmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool vma_is_shmem(struct vm_area_struct * vma)
```
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
