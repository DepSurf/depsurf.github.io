# Function: <code>mmap_is_ia32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579058051,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:345",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301478,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054419,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:345",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300758,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053523,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:354",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579316214,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:354",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579045749,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579313788,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684577,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696018,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054471,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336444,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581830156,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841718,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059521,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579347301,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582010044,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024932,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:302",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579064097,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579374245,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097947,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113012,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579072678,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579389701,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582259026,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273999,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579074678,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579393013,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226684,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358449,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579085270,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407157,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414380,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582651155,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582662863,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579087334,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407637,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457228,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721561,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731788,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579093942,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410981,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478172,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750479,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760491,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:320",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579117238,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473765,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732364,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077407,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087403,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:321",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579150495,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:310",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551301,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:310",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112743,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:310",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583555709,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:310",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566518,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:310",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int mmap_is_ia32()
```

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579197782,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657893,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586567,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157188,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584168553,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153936,
      "name": "mmap_is_ia32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int mmap_is_ia32()
```

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201830,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579672117,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582793879,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584384841,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584396489,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:305",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381568,
      "name": "mmap_is_ia32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231094,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:306",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr",
        "arch/x86/kernel/sys_x86_64.c:align_vdso_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706005,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:306",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968903,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:306",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584603093,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:306",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614741,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:306",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579075030,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579388917,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195532,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327185,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579007926,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579318469,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142284,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264945,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579074614,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579388837,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186732,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317665,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
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
  "name": "mmap_is_ia32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078710,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/kernel/sys_x86_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579397365,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_mmap_rnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249980,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:randomize_stack_top"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396897,
      "name": "mmap_is_ia32",
      "external": false,
      "loc": "arch/x86/include/asm/elf.h:301",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int mmap_is_ia32()
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int mmap_is_ia32()
```
</details>
</li>
</ul>
