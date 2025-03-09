# Function: <code>get_random_int</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int get_random_int()
```

```json
{
  "name": "get_random_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164816,
      "name": "get_random_int",
      "external": true,
      "loc": "drivers/char/random.c:1802",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "kernel/fork.c:copy_process",
        "mm/mempolicy.c:node_random",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "drivers/char/random.c:randomize_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164816,
      "name": "get_random_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
unsigned int get_random_int()
```

```json
{
  "name": "get_random_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503120,
      "name": "get_random_int",
      "external": true,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "mm/slub.c:new_slab",
        "lib/nodemask.c:node_random",
        "drivers/char/random.c:randomize_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503120,
      "name": "get_random_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
unsigned int get_random_int()
```

```json
{
  "name": "get_random_int",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584685232,
      "name": "get_random_int",
      "external": true,
      "loc": "drivers/char/random.c:2062",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "mm/slub.c:new_slab",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584685232,
      "name": "get_random_int",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861741,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067157,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108206,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248713,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580481265,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097506,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587295937,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216650,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:48",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862349,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076262,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124315,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265420,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580539768,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216952,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817761,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766618,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864302,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081558,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130384,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276613,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580623787,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354249,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588160938,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145434,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:49",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864142,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087030,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137120,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300501,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580683793,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765374,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438030,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588344906,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380570,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:50",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864766,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096725,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148482,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317112,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580739349,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831893,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842600,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549190,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588746810,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837626,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:51",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864894,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098709,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150930,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321144,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790069,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883188,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893640,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613940,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588970567,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063770,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578868061,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111189,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170820,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350616,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907733,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984576,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581038928,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833876,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585060682,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589924183,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863501,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111029,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167361,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350456,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903628,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993196,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581047328,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879806,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209978,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964727,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863897,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117685,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173412,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355096,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907292,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009657,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581062158,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911525,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092970,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589879623,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578865481,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143141,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206932,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412728,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109484,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224958,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287344,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206901,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540554,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590643527,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:54",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862753,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:arch_setup_additional_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180763,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258063,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479724,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375800,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510408,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581583679,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616644,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671863,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736834,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695274,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592266190,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:43",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490194664,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492103864,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492208168,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492219124,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493063444,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502573024,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503841036,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224417940,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/arm/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/process.c:arch_setup_additional_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3224431804,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/arm/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/signal.c:get_signal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226004112,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226105628,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3226118988,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226770068,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 3235280132,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282306688,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285305996,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285427848,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285443984,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286498300,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296159584,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297692500,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272278952,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272357456,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272369216,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272925838,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278731404,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864894,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099093,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151298,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317048,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580758869,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580851988,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580862440,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582676,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588576951,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589666026,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858462,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031525,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082594,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251640,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580705045,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580798164,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580808568,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524225,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588288935,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391850,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864830,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098645,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150850,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316968,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750117,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843236,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853688,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573988,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589013127,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590109402,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
  "name": "get_random_int",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578865150,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103093,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155986,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325256,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580808213,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901524,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912019,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639236,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589051719,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_genid_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159738,
      "name": "get_random_int",
      "external": false,
      "loc": "include/linux/random.h:52",
      "file": "lib/nodemask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nodemask.c:node_random"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
unsigned int get_random_int()
```
</details>
</li>
</ul>
