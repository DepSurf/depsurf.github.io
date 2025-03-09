# Function: <code>copy_kernel_to_fpregs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031387,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:463",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081753,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:463",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579027593,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:460",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078693,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:460",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579027072,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:455",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077380,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:455",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579019333,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:465",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069286,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:465",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579022753,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:443",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078198,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:443",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
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
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579026881,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:443",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084054,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:443",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end"
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
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031594,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:446",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089126,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:446",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_end"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579098870,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105114,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579100853,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106954,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state * fpstate)
```

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112576,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:461",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save"
      ]
    },
    {
      "addr": 18446744071579117808,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:461",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112576,
      "name": "copy_kernel_to_fpregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071579117808,
      "name": "copy_kernel_to_fpregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state * fpstate)
```

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113968,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:428",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save"
      ]
    },
    {
      "addr": 18446744071579117600,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:428",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113968,
      "name": "copy_kernel_to_fpregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071579117600,
      "name": "copy_kernel_to_fpregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state * fpstate)
```

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120624,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:419",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save"
      ]
    },
    {
      "addr": 18446744071579124224,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:419",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120624,
      "name": "copy_kernel_to_fpregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579124224,
      "name": "copy_kernel_to_fpregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579101237,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107338,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579033653,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039754,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579100789,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106890,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_kernel_to_fpregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579105317,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111918,
      "name": "copy_kernel_to_fpregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:457",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state * fpstate)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state * fpstate)
```
</details>
</li>
</ul>
