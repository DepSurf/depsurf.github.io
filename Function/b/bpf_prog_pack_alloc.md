# Function: <code>bpf_prog_pack_alloc</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns)
```

```json
{
  "name": "bpf_prog_pack_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385136,
      "name": "bpf_prog_pack_alloc",
      "external": false,
      "loc": "kernel/bpf/core.c:895",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385136,
      "name": "bpf_prog_pack_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void * bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns)
```

```json
{
  "name": "bpf_prog_pack_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739104,
      "name": "bpf_prog_pack_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:876",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739104,
      "name": "bpf_prog_pack_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void * bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns)
```

```json
{
  "name": "bpf_prog_pack_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898576,
      "name": "bpf_prog_pack_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:877",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898576,
      "name": "bpf_prog_pack_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void * bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns)
```

```json
{
  "name": "bpf_prog_pack_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023088,
      "name": "bpf_prog_pack_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:920",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_alloc_bpf_trampoline",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023088,
      "name": "bpf_prog_pack_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void * bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns)
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
