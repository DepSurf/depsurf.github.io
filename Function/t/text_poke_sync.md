# Function: <code>text_poke_sync</code>

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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579095134,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:994",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097424,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096296,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1006",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098688,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102488,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:927",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105376,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579126408,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:927",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129456,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160767,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1300",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164992,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210975,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1770",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217888,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579216518,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1995",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:clear_relocate_add",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223328,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void text_poke_sync()
```

```json
{
  "name": "text_poke_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579245894,
      "name": "text_poke_sync",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:2085",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/module.c:clear_relocate_add",
        "arch/x86/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252192,
      "name": "text_poke_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void text_poke_sync()
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
