# Function: <code>user_regset_copyin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579084141,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:245",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:xfpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:fpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579083679,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:245",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081871,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:245",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579073439,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:245",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082319,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:282",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085664,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:282",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085664,
      "name": "user_regset_copyin.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579091040,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:282",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579091040,
      "name": "user_regset_copyin.constprop.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102817,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100512,
      "name": "user_regset_copyin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104625,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579117345,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579117297,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123921,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579149251,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579190630,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246966,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244944,
      "name": "user_regset_copyin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579251296,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251296,
      "name": "user_regset_copyin.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579280720,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:253",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:ssp_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280720,
      "name": "user_regset_copyin.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int user_regset_copyin(unsigned int * pos, unsigned int * count, const void * * kbuf, const void * * ubuf, void * data, const int start_pos, const int end_pos)
```

```json
{
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490204184,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_tls_set",
        "arch/arm64/kernel/ptrace.c:compat_vfp_set",
        "arch/arm64/kernel/ptrace.c:pac_generic_keys_set",
        "arch/arm64/kernel/ptrace.c:pac_address_keys_set",
        "arch/arm64/kernel/ptrace.c:sve_set",
        "arch/arm64/kernel/ptrace.c:system_call_set",
        "arch/arm64/kernel/ptrace.c:tls_set",
        "arch/arm64/kernel/ptrace.c:gpr_set",
        "arch/arm64/kernel/ptrace.c:hw_break_set",
        "arch/arm64/kernel/ptrace.c:hw_break_set",
        "arch/arm64/kernel/ptrace.c:hw_break_set"
      ],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:compat_vfp_set",
        "arch/arm64/kernel/ptrace.c:sve_set",
        "arch/arm64/kernel/ptrace.c:sve_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490208736,
      "name": "user_regset_copyin",
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224421664,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:vfp_set",
        "arch/arm/kernel/ptrace.c:vfp_set",
        "arch/arm/kernel/ptrace.c:fpa_set",
        "arch/arm/kernel/ptrace.c:gpr_set"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int user_regset_copyin(unsigned int * pos, unsigned int * count, const void * * kbuf, const void * * ubuf, void * data, const int start_pos, const int end_pos)
```

```json
{
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282253596,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:pmu_set",
        "arch/powerpc/kernel/ptrace.c:ebb_set",
        "arch/powerpc/kernel/ptrace.c:ebb_set",
        "arch/powerpc/kernel/ptrace.c:ebb_set",
        "arch/powerpc/kernel/ptrace.c:tar_set",
        "arch/powerpc/kernel/ptrace.c:dscr_set",
        "arch/powerpc/kernel/ptrace.c:ppr_set",
        "arch/powerpc/kernel/ptrace.c:tm_dscr_set",
        "arch/powerpc/kernel/ptrace.c:tm_ppr_set",
        "arch/powerpc/kernel/ptrace.c:tm_tar_set",
        "arch/powerpc/kernel/ptrace.c:tm_spr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cvmx_set",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_set",
        "arch/powerpc/kernel/ptrace.c:vr_set",
        "arch/powerpc/kernel/ptrace.c:gpr_set",
        "arch/powerpc/kernel/ptrace.c:gpr_set"
      ],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:pmu_set",
        "arch/powerpc/kernel/ptrace.c:pmu_set",
        "arch/powerpc/kernel/ptrace.c:pmu_set",
        "arch/powerpc/kernel/ptrace.c:pmu_set",
        "arch/powerpc/kernel/ptrace.c:tm_spr_set",
        "arch/powerpc/kernel/ptrace.c:tm_spr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cvsx_set",
        "arch/powerpc/kernel/ptrace.c:tm_cvmx_set",
        "arch/powerpc/kernel/ptrace.c:tm_cfpr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_set",
        "arch/powerpc/kernel/ptrace.c:vsr_set",
        "arch/powerpc/kernel/ptrace.c:vr_set",
        "arch/powerpc/kernel/ptrace.c:fpr_set",
        "arch/powerpc/kernel/ptrace.c:gpr_set",
        "arch/powerpc/kernel/ptrace.c:gpr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282242624,
      "name": "user_regset_copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271343982,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/ptrace.c:riscv_fpr_set",
        "arch/riscv/kernel/ptrace.c:riscv_fpr_set",
        "arch/riscv/kernel/ptrace.c:riscv_gpr_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579105009,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579037425,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104561,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
  "name": "user_regset_copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579109393,
      "name": "user_regset_copyin",
      "external": false,
      "loc": "include/linux/regset.h:279",
      "file": "arch/x86/kernel/fpu/regset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/regset.c:fpregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xfpregs_set"
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
int user_regset_copyin(unsigned int * pos, unsigned int * count, const void * * kbuf, const void * * ubuf, void * data, const int start_pos, const int end_pos)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int user_regset_copyin(unsigned int * pos, unsigned int * count, const void * * kbuf, const void * * ubuf, void * data, const int start_pos, const int end_pos)
```
</details>
</li>
</ul>
