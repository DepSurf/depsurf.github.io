# Function: <code>arch_futex_atomic_op_inuser</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580013783,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580070698,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580110713,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147872,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147872,
      "name": "arch_futex_atomic_op_inuser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195888,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195888,
      "name": "arch_futex_atomic_op_inuser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580264838,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:56",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580248502,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:56",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580253654,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:56",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580404822,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:56",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580641092,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:48",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907668,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:48",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580992228,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:48",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581087204,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:48",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491447708,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/arm64/include/asm/futex.h:46",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225420936,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/arm/include/asm/futex.h:133",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284378196,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/powerpc/include/asm/futex.h:33",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271902476,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/riscv/include/asm/futex.h:39",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164688,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164688,
      "name": "arch_futex_atomic_op_inuser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112304,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112304,
      "name": "arch_futex_atomic_op_inuser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156160,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156160,
      "name": "arch_futex_atomic_op_inuser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```

```json
{
  "name": "arch_futex_atomic_op_inuser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208176,
      "name": "arch_futex_atomic_op_inuser",
      "external": false,
      "loc": "arch/x86/include/asm/futex.h:45",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208176,
      "name": "arch_futex_atomic_op_inuser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_futex_atomic_op_inuser(int op, int oparg, int * oval, u32 * uaddr)
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
