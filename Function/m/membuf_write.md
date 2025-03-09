# Function: <code>membuf_write</code>

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
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579116874,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122706,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_part",
        "arch/x86/kernel/fpu/xstate.c:copy_part"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125116,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133322,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tls.c:regset_tls_get"
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
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123498,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128525,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132367,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140000,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tls.c:regset_tls_get"
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
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579148996,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155927,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158703,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166896,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tls.c:regset_tls_get"
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
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579190312,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199598,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203951,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212382,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tls.c:regset_tls_get"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int membuf_write(struct membuf * s, const void * v, size_t size)
```

```json
{
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579244384,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    },
    {
      "addr": 18446744071579251232,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf"
      ]
    },
    {
      "addr": 18446744071579259215,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268094,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tls.c:regset_tls_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244384,
      "name": "membuf_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071579251232,
      "name": "membuf_write.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int membuf_write(struct membuf * s, const void * v, size_t size)
```

```json
{
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579250736,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    },
    {
      "addr": 18446744071579257712,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf"
      ]
    },
    {
      "addr": 18446744071579265439,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272624,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tls.c:regset_tls_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250736,
      "name": "membuf_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071579257712,
      "name": "membuf_write.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579272624,
      "name": "membuf_write.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int membuf_write(struct membuf * s, const void * v, size_t size)
```

```json
{
  "name": "membuf_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579280160,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:ssp_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    },
    {
      "addr": 18446744071579287552,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf"
      ]
    },
    {
      "addr": 18446744071579295263,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302448,
      "name": "membuf_write",
      "external": false,
      "loc": "include/linux/regset.h:37",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tls.c:regset_tls_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280160,
      "name": "membuf_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071579287552,
      "name": "membuf_write.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579302448,
      "name": "membuf_write.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int membuf_write(struct membuf * s, const void * v, size_t size)
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
