# Function: <code>emit_mov_imm32</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403408,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:328",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403408,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434848,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:328",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434848,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450624,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:297",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450624,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476688,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:297",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476688,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579499312,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:483",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499312,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480128,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:601",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480128,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496967,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:616",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482096,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551376,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:610",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551376,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641040,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:611",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641040,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758832,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:624",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758832,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805408,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:624",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805408,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840512,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:758",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_mov_imm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840512,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450352,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:297",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450352,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379328,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:297",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379328,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450272,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:297",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450272,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```

```json
{
  "name": "emit_mov_imm32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482016,
      "name": "emit_mov_imm32",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:297",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482016,
      "name": "emit_mov_imm32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void emit_mov_imm32(u8 * * pprog, bool sign_propagate, u32 dst_reg, const u32 imm32)
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
