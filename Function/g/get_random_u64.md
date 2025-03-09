# Function: <code>get_random_u64</code>

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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778352,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2094",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
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
      "addr": 18446744071584778352,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198448,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2093",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/slub.c:__kmem_cache_create",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198448,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585433680,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2201",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/slub.c:kmem_cache_open",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433680,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559280,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2226",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/slub.c:kmem_cache_open",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559280,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777728,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2310",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777728,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585920432,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920432,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653696,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2191",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:init_listener",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653696,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764400,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2190",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:init_listener",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:prandom_reseed",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764400,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586645536,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2166",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:prandom_reseed",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645536,
      "name": "get_random_u64",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192624,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2191",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "lib/random32.c:prandom_reseed",
        "lib/random32.c:prandom_reseed",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192624,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499920,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:509",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499920,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589936080,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:533",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589936080,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590246080,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:533",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246080,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590587104,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:533",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_page",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/shuffle.c:shuffle_pick_tail",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590587104,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498741608,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kvm/va_layout.c:compute_layout",
        "kernel/fork.c:dup_task_struct",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:arch_mmap_rnd",
        "mm/util.c:arch_mmap_rnd",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498741608,
      "name": "get_random_u64",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231360964,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/shuffle.c:add_to_free_area_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231360964,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291896160,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/powerpc/kernel/process.c:arch_randomize_brk",
        "arch/powerpc/kernel/process.c:arch_randomize_brk",
        "arch/powerpc/kernel/smp.c:start_secondary",
        "arch/powerpc/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291896160,
      "name": "get_random_u64",
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276243610,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:arch_pick_mmap_layout",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276243610,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681408,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681408,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541280,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541280,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870832,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870832,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 get_random_u64()
```

```json
{
  "name": "get_random_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978736,
      "name": "get_random_u64",
      "external": true,
      "loc": "drivers/char/random.c:2371",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:add_to_free_area_random",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "drivers/char/random.c:randomize_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978736,
      "name": "get_random_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 get_random_u64()
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
