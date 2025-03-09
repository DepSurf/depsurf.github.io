# Function: <code>get_random_long</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_random_long()
```

```json
{
  "name": "get_random_long",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584506944,
      "name": "get_random_long",
      "external": true,
      "loc": "drivers/char/random.c:2084",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "mm/slab_common.c:cache_random_seq_create",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506944,
      "name": "get_random_long",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int get_random_long()
```

```json
{
  "name": "get_random_long",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689056,
      "name": "get_random_long",
      "external": true,
      "loc": "drivers/char/random.c:2084",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "mm/slab_common.c:cache_random_seq_create",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689056,
      "name": "get_random_long",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579314077,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376864,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580842663,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683444,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696013,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584778890,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336733,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403685,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580933351,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232394,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829023,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841713,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198986,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579347477,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419401,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581069341,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368489,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582010349,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024927,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435991,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:53",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579374421,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450657,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581147149,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457344,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582098261,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113007,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585559639,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389875,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468883,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213917,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589943627,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571576,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582259318,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273994,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779431,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:55",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393187,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494957,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226679,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272573,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171182,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636792,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585922135,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407349,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523803,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414375,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462646,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189542,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853942,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586659127,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407829,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505618,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457223,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502986,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591685005,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902594,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584747590,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:prandom_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769639,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579411173,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509057,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478167,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525194,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591627868,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933216,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584775926,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:prandom_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586650284,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579473957,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578161,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732359,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787146,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592801672,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232150,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205882,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:prandom_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587198108,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:58",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551525,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:47",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668987,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:47",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112844,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:47",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172366,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:47",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594702057,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:47",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582701352,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:47",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627477873,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627560584,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658133,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789035,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586684,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656622,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596443446,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226264,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619221472,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619309912,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579672357,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836507,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582793996,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596984758,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445016,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621511173,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621602990,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706245,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876510,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969020,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597913286,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429224,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:44",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490481872,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/arm64/kvm/va_layout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/va_layout.c:compute_layout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490627372,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492616344,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:arch_mmap_rnd",
        "mm/util.c:arch_mmap_rnd",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492677936,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503919404,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493085636,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498747828,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224706520,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226467884,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:arch_pick_mmap_layout",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 3226516536,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3244024488,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 3226792876,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3231369488,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302365596,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282306832,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/process.c:arch_randomize_brk",
        "arch/powerpc/kernel/process.c:arch_randomize_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282517036,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282722744,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/powerpc/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283446788,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285933760,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286004144,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297814528,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286532488,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291905888,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272642264,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:arch_pick_mmap_layout",
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272684606,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270890630,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272943636,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276251034,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389091,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468621,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195527,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241421,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773470,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605528,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585683111,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579318643,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397523,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142279,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188093,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589496293,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546872,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585542983,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389011,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468541,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186727,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232621,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590216878,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596840,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872535,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397539,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500276,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249975,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296157,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590267241,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:__shuffle_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662696,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585980407,
      "name": "get_random_long",
      "external": false,
      "loc": "include/linux/random.h:56",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:randomize_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long unsigned int get_random_long()
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
long unsigned int get_random_long()
```
</details>
</li>
</ul>
