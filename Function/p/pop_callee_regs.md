# Function: <code>pop_callee_regs</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480032,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:243",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480032,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482000,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:255",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482000,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:254",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548816,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071592096725,
      "name": "pop_callee_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:272",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637600,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071593864117,
      "name": "pop_callee_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:273",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754880,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071595972694,
      "name": "pop_callee_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:273",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801456,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071596490321,
      "name": "pop_callee_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```

```json
{
  "name": "pop_callee_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pop_callee_regs",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:295",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834928,
      "name": "pop_callee_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071597386999,
      "name": "pop_callee_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void pop_callee_regs(u8 * * pprog, bool * callee_regs_used)
```
</details>
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
