# Function: <code>x86_call_depth_emit_accounting</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int x86_call_depth_emit_accounting(u8 * * pprog, void * func)
```

```json
{
  "name": "x86_call_depth_emit_accounting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_call_depth_emit_accounting",
      "external": true,
      "loc": "arch/x86/kernel/callthunks.c:310",
      "file": "arch/x86/kernel/callthunks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595968294,
      "name": "x86_call_depth_emit_accounting.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579627984,
      "name": "x86_call_depth_emit_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int x86_call_depth_emit_accounting(u8 * * pprog, void * func)
```

```json
{
  "name": "x86_call_depth_emit_accounting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_call_depth_emit_accounting",
      "external": true,
      "loc": "arch/x86/kernel/callthunks.c:310",
      "file": "arch/x86/kernel/callthunks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596485892,
      "name": "x86_call_depth_emit_accounting.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071579641952,
      "name": "x86_call_depth_emit_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int x86_call_depth_emit_accounting(u8 * * pprog, void * func)
```

```json
{
  "name": "x86_call_depth_emit_accounting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_call_depth_emit_accounting",
      "external": true,
      "loc": "arch/x86/kernel/callthunks.c:303",
      "file": "arch/x86/kernel/callthunks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597382502,
      "name": "x86_call_depth_emit_accounting.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071579671760,
      "name": "x86_call_depth_emit_accounting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int x86_call_depth_emit_accounting(u8 * * pprog, void * func)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
