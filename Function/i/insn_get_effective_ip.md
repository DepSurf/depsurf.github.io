# Function: <code>insn_get_effective_ip</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585281621,
      "name": "insn_get_effective_ip",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1418",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585165061,
      "name": "insn_get_effective_ip",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1420",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_get_effective_ip(struct pt_regs * regs, long unsigned int * ip)
```

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585618469,
      "name": "insn_get_effective_ip",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:1420",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618256,
      "name": "insn_get_effective_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int insn_get_effective_ip(struct pt_regs * regs, long unsigned int * ip)
```

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586776741,
      "name": "insn_get_effective_ip",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:1465",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776416,
      "name": "insn_get_effective_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int insn_get_effective_ip(struct pt_regs * regs, long unsigned int * ip)
```

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595942581,
      "name": "insn_get_effective_ip",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:1465",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595942224,
      "name": "insn_get_effective_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int insn_get_effective_ip(struct pt_regs * regs, long unsigned int * ip)
```

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596460869,
      "name": "insn_get_effective_ip",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:1465",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596460512,
      "name": "insn_get_effective_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int insn_get_effective_ip(struct pt_regs * regs, long unsigned int * ip)
```

```json
{
  "name": "insn_get_effective_ip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597355893,
      "name": "insn_get_effective_ip",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:1465",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597355536,
      "name": "insn_get_effective_ip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int insn_get_effective_ip(struct pt_regs * regs, long unsigned int * ip)
```
</details>
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
