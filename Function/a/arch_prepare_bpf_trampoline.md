# Function: <code>arch_prepare_bpf_trampoline</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int arch_prepare_bpf_trampoline(void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_progs * tprogs, void * orig_call)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069872,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:1574",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513544,
      "name": "arch_prepare_bpf_trampoline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579510784,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1372
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_progs * tprogs, void * orig_call)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084592,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:1747",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591276478,
      "name": "arch_prepare_bpf_trampoline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579492640,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1578
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_progs * tprogs, void * orig_call)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103088,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:1958",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591219362,
      "name": "arch_prepare_bpf_trampoline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579496240,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1664
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_progs * tprogs, void * orig_call)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332720,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2003",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592097793,
      "name": "arch_prepare_bpf_trampoline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579566320,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2072
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_links * tlinks, void * orig_call)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637712,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2022",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593864955,
      "name": "arch_prepare_bpf_trampoline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071579655888,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2306
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_links * tlinks, void * func_addr)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774128,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2128",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774128,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2700
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_links * tlinks, void * func_addr)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820928,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2133",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820928,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2635
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
int arch_prepare_bpf_trampoline(struct bpf_tramp_image * im, void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_links * tlinks, void * func_addr)
```

```json
{
  "name": "arch_prepare_bpf_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860704,
      "name": "arch_prepare_bpf_trampoline",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2791",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_prepare_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860704,
      "name": "arch_prepare_bpf_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int arch_prepare_bpf_trampoline(void * image, void * image_end, const struct btf_func_model * m, u32 flags, struct bpf_tramp_progs * tprogs, void * orig_call)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_tramp_image * im</code>
</li>
<li>
<b>Param reordered. </b>
<code>image, image_end, m, flags, tprogs, orig_call</code> ➡️ <code>im, image, image_end, m, flags, tprogs, orig_call</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_tramp_links * tlinks</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_tramp_progs * tprogs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * func_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>void * orig_call</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
