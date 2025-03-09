# Function: <code>copy_fpregs_to_fpstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579030797,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:430",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082042,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:430",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:fpu__copy"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579026877,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:427",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079851,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:427",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579027406,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:422",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078133,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:422",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579019725,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:432",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069907,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:432",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579023138,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:410",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078991,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:410",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579027266,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:410",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084435,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:410",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031996,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:413",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089811,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:413",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579039614,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099708,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579042014,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101692,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
int copy_fpregs_to_fpstate(struct fpu * fpu)
```

```json
{
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050192,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:421",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ]
    },
    {
      "addr": 18446744071579112352,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:421",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050192,
      "name": "copy_fpregs_to_fpstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071579112352,
      "name": "copy_fpregs_to_fpstate",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_fpregs_to_fpstate(struct fpu * fpu)
```

```json
{
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112560,
      "name": "copy_fpregs_to_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:95",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112560,
      "name": "copy_fpregs_to_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int copy_fpregs_to_fpstate(struct fpu * fpu)
```

```json
{
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579119216,
      "name": "copy_fpregs_to_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:95",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119216,
      "name": "copy_fpregs_to_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579042366,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102076,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578975406,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034492,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579041950,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101628,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
  "name": "copy_fpregs_to_fpstate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579045614,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106328,
      "name": "copy_fpregs_to_fpstate",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:417",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
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
int copy_fpregs_to_fpstate(struct fpu * fpu)
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
int copy_fpregs_to_fpstate(struct fpu * fpu)
```
</details>
</li>
</ul>
