# Function: <code>__vmalloc_node_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580741712,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1653",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:__vmalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741712,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860896,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1674",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860896,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931200,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1688",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc",
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931200,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580975440,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1749",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975440,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078064,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1741",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078064,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581216992,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1728",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216992,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581300720,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:1734",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300720,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581377856,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2472",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:copy_process",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377856,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439056,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:copy_process",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439056,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648176,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2527",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648176,
      "name": "__vmalloc_node_range",
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694560,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2560",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694560,
      "name": "__vmalloc_node_range",
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717616,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2866",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_no_huge",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717616,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989936,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2970",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_no_huge",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989936,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:3081",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module/main.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_huge",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593979368,
      "name": "__vmalloc_node_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582412352,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:3143",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module/main.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_huge",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596035341,
      "name": "__vmalloc_node_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582919904,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:3236",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module/main.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_huge",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596557474,
      "name": "__vmalloc_node_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583136064,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:3236",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:alloc_thread_stack_node",
        "kernel/module/main.c:module_alloc",
        "kernel/bpf/syscall.c:__bpf_map_area_alloc",
        "mm/util.c:kvmalloc_node",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vmalloc_huge",
        "mm/vmalloc.c:__vmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597461718,
      "name": "__vmalloc_node_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583319184,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492842680,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/irq.c:init_IRQ",
        "arch/arm64/kernel/module.c:module_alloc",
        "arch/arm64/kernel/module.c:module_alloc",
        "arch/arm64/kernel/module.c:module_alloc",
        "arch/arm64/kernel/sdei.c:_init_sdei_stack",
        "arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec",
        "kernel/fork.c:dup_task_struct",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492842680,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226649444,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226649444,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286231424,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286231424,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272794564,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/module.c:module_alloc",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272794564,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581407904,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:copy_process",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407904,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581350416,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:copy_process",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350416,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581399104,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:copy_process",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399104,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
void * __vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void * caller)
```

```json
{
  "name": "__vmalloc_node_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581463120,
      "name": "__vmalloc_node_range",
      "external": true,
      "loc": "mm/vmalloc.c:2480",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/fork.c:copy_process",
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller",
        "mm/vmalloc.c:__vmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463120,
      "name": "__vmalloc_node_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
