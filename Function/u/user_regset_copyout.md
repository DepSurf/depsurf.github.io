# Function: <code>user_regset_copyout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579083996,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:xfpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:fpregs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579092649,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579083378,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
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
      "addr": 18446744071579091941,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081570,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
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
      "addr": 18446744071579090037,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579073078,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
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
      "addr": 18446744071579081925,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:220",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081958,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:257",
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
      "addr": 18446744071579092677,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:257",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085824,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:257",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    },
    {
      "addr": 18446744071579098032,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:257",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085824,
      "name": "user_regset_copyout.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579098032,
      "name": "user_regset_copyout.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579091200,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:257",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    },
    {
      "addr": 18446744071579103616,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:257",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579091200,
      "name": "user_regset_copyout.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579103616,
      "name": "user_regset_copyout.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102400,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    },
    {
      "addr": 18446744071579113365,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100672,
      "name": "user_regset_copyout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104208,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
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
      "addr": 18446744071579115285,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579116928,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
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
      "addr": 18446744071579126437,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int user_regset_copyout(unsigned int * pos, unsigned int * count, void * * kbuf, void * * ubuf, const void * data, const int start_pos, const int end_pos)
```

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490202528,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_tls_get",
        "arch/arm64/kernel/ptrace.c:compat_vfp_get",
        "arch/arm64/kernel/ptrace.c:pac_generic_keys_get",
        "arch/arm64/kernel/ptrace.c:pac_address_keys_get",
        "arch/arm64/kernel/ptrace.c:pac_mask_get",
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:system_call_get",
        "arch/arm64/kernel/ptrace.c:tls_get",
        "arch/arm64/kernel/ptrace.c:fpr_get",
        "arch/arm64/kernel/ptrace.c:gpr_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get"
      ],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:compat_vfp_get",
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490210712,
      "name": "user_regset_copyout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224421224,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:vfp_get",
        "arch/arm/kernel/ptrace.c:vfp_get",
        "arch/arm/kernel/ptrace.c:fpa_get",
        "arch/arm/kernel/ptrace.c:gpr_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282246452,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:pmu_get",
        "arch/powerpc/kernel/ptrace.c:ebb_get",
        "arch/powerpc/kernel/ptrace.c:tar_get",
        "arch/powerpc/kernel/ptrace.c:dscr_get",
        "arch/powerpc/kernel/ptrace.c:ppr_get",
        "arch/powerpc/kernel/ptrace.c:tm_dscr_get",
        "arch/powerpc/kernel/ptrace.c:tm_ppr_get",
        "arch/powerpc/kernel/ptrace.c:tm_tar_get",
        "arch/powerpc/kernel/ptrace.c:tm_spr_get",
        "arch/powerpc/kernel/ptrace.c:tm_spr_get",
        "arch/powerpc/kernel/ptrace.c:tm_spr_get",
        "arch/powerpc/kernel/ptrace.c:tm_cvsx_get",
        "arch/powerpc/kernel/ptrace.c:tm_cvmx_get",
        "arch/powerpc/kernel/ptrace.c:tm_cvmx_get",
        "arch/powerpc/kernel/ptrace.c:tm_cfpr_get",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:vsr_get",
        "arch/powerpc/kernel/ptrace.c:vr_get",
        "arch/powerpc/kernel/ptrace.c:vr_get",
        "arch/powerpc/kernel/ptrace.c:fpr_get",
        "arch/powerpc/kernel/ptrace.c:gpr_get",
        "arch/powerpc/kernel/ptrace.c:gpr_get",
        "arch/powerpc/kernel/ptrace.c:gpr_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271343670,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/ptrace.c:riscv_fpr_get",
        "arch/riscv/kernel/ptrace.c:riscv_fpr_get",
        "arch/riscv/kernel/ptrace.c:riscv_gpr_get"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104592,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
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
      "addr": 18446744071579115669,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579037008,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
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
      "addr": 18446744071579047765,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104144,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
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
      "addr": 18446744071579115221,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
  "name": "user_regset_copyout",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579108976,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
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
      "addr": 18446744071579120309,
      "name": "user_regset_copyout",
      "external": false,
      "loc": "include/linux/regset.h:254",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ioperm_get"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int user_regset_copyout(unsigned int * pos, unsigned int * count, void * * kbuf, void * * ubuf, const void * data, const int start_pos, const int end_pos)
```
</details>
</li>
</ul>
