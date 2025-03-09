# Function: <code>get_mem_cgroup_from_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921328,
      "name": "get_mem_cgroup_from_mm",
      "external": false,
      "loc": "mm/memcontrol.c:831",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:__memcg_kmem_get_cache",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921328,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066336,
      "name": "get_mem_cgroup_from_mm",
      "external": false,
      "loc": "mm/memcontrol.c:724",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066336,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141584,
      "name": "get_mem_cgroup_from_mm",
      "external": false,
      "loc": "mm/memcontrol.c:726",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141584,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189040,
      "name": "get_mem_cgroup_from_mm",
      "external": false,
      "loc": "mm/memcontrol.c:696",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189040,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317696,
      "name": "get_mem_cgroup_from_mm",
      "external": false,
      "loc": "mm/memcontrol.c:710",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317696,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464112,
      "name": "get_mem_cgroup_from_mm",
      "external": false,
      "loc": "mm/memcontrol.c:681",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464112,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581551376,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:827",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551376,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581664464,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:944",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664464,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735680,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735680,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581955200,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:916",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955200,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582001536,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:1019",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001536,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582027664,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:897",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027664,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330272,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:948",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330272,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582833408,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:930",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "kernel/bpf/syscall.c:map_create",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582833408,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375792,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:1010",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375792,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583595264,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:1035",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583595264,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791632,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:1078",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "mm/vmscan.c:lru_gen_add_mm",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791632,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493197352,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493197352,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226845636,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226822380,
      "name": "get_mem_cgroup_from_mm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 3226822588,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286688736,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286688736,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272991084,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272970094,
      "name": "get_mem_cgroup_from_mm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446743936272970260,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581704416,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704416,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581643632,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643632,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581695728,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695728,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct mem_cgroup * get_mem_cgroup_from_mm(struct mm_struct * mm)
```

```json
{
  "name": "get_mem_cgroup_from_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581763552,
      "name": "get_mem_cgroup_from_mm",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763552,
      "name": "get_mem_cgroup_from_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
