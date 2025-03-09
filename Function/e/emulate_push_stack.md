# Function: <code>emulate_push_stack</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298848,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:535",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298848,
      "name": "emulate_push_stack.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323440,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:535",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323440,
      "name": "emulate_push_stack.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338736,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338736,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579342912,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342912,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372432,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372432,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371072,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371072,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374768,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374768,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436240,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436240,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505888,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505888,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604544,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604544,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616912,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616912,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645968,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:526",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645968,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338816,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338816,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271216,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271216,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338736,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338736,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```

```json
{
  "name": "emulate_push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347184,
      "name": "emulate_push_stack",
      "external": false,
      "loc": "arch/x86/kernel/uprobes.c:525",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:push_emulate_op",
        "arch/x86/kernel/uprobes.c:branch_emulate_op",
        "arch/x86/kernel/uprobes.c:default_post_xol_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347184,
      "name": "emulate_push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int emulate_push_stack(struct pt_regs * regs, long unsigned int val)
```
</details>
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
