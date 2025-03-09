# Function: <code>bpf_arch_text_copy</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_arch_text_copy(void * dst, void * src, size_t len)
```

```json
{
  "name": "bpf_arch_text_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659106,
      "name": "bpf_arch_text_copy",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2503",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659856,
      "name": "bpf_arch_text_copy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_arch_text_copy(void * dst, void * src, size_t len)
```

```json
{
  "name": "bpf_arch_text_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777766,
      "name": "bpf_arch_text_copy",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2623",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778688,
      "name": "bpf_arch_text_copy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_arch_text_copy(void * dst, void * src, size_t len)
```

```json
{
  "name": "bpf_arch_text_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579824290,
      "name": "bpf_arch_text_copy",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:2626",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825360,
      "name": "bpf_arch_text_copy",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_arch_text_copy(void * dst, void * src, size_t len)
```

```json
{
  "name": "bpf_arch_text_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579861858,
      "name": "bpf_arch_text_copy",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:3135",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862960,
      "name": "bpf_arch_text_copy",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void * bpf_arch_text_copy(void * dst, void * src, size_t len)
```
</details>
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
