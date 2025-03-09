# Function: <code>bpf_arch_text_poke</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510672,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:329",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510672,
      "name": "bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492528,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:364",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492528,
      "name": "bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496128,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:376",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496128,
      "name": "bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566208,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:372",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566208,
      "name": "bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655696,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:391",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655696,
      "name": "bpf_arch_text_poke",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773904,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:399",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:__bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773904,
      "name": "bpf_arch_text_poke",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820704,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:399",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:__bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820704,
      "name": "bpf_arch_text_poke",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "bpf_arch_text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860320,
      "name": "bpf_arch_text_poke",
      "external": true,
      "loc": "arch/x86/net/bpf_jit_comp.c:521",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog",
        "kernel/bpf/trampoline.c:__bpf_trampoline_link_prog",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860320,
      "name": "bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
