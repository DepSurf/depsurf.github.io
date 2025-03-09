# Function: <code>bpf_jit_alloc_exec_page</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_jit_alloc_exec_page()
```

```json
{
  "name": "bpf_jit_alloc_exec_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581069093,
      "name": "bpf_jit_alloc_exec_page",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:26",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_lookup"
      ],
      "caller_func": [
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068688,
      "name": "bpf_jit_alloc_exec_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * bpf_jit_alloc_exec_page()
```

```json
{
  "name": "bpf_jit_alloc_exec_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581083451,
      "name": "bpf_jit_alloc_exec_page",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:28",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_tramp_image_alloc"
      ],
      "caller_func": [
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083712,
      "name": "bpf_jit_alloc_exec_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * bpf_jit_alloc_exec_page()
```

```json
{
  "name": "bpf_jit_alloc_exec_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581103667,
      "name": "bpf_jit_alloc_exec_page",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:29",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ],
      "caller_func": [
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101744,
      "name": "bpf_jit_alloc_exec_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_jit_alloc_exec_page()
```

```json
{
  "name": "bpf_jit_alloc_exec_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581333435,
      "name": "bpf_jit_alloc_exec_page",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:29",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ],
      "caller_func": [
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331376,
      "name": "bpf_jit_alloc_exec_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * bpf_jit_alloc_exec_page()
```

```json
{
  "name": "bpf_jit_alloc_exec_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581638355,
      "name": "bpf_jit_alloc_exec_page",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:41",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ],
      "caller_func": [
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636064,
      "name": "bpf_jit_alloc_exec_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
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
void * bpf_jit_alloc_exec_page()
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void * bpf_jit_alloc_exec_page()
```
</details>
</li>
</ul>
