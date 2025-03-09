# Function: <code>using_compacted_format</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595007561,
      "name": "using_compacted_format",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:404",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595171788,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087216,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595414140,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:480",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085392,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596333406,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:481",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076976,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579088945,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085456,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579094287,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090832,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579099708,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096144,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604712603,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:469",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106560,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604724436,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:469",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108384,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125174,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:507",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121536,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591250533,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:512",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121680,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591194291,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:547",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127904,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604650739,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:469",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108768,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604618531,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:469",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041152,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604728502,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:469",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108320,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int using_compacted_format()
```

```json
{
  "name": "using_compacted_format",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604728548,
      "name": "using_compacted_format",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:469",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113392,
      "name": "using_compacted_format",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int using_compacted_format()
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int using_compacted_format()
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
int using_compacted_format()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int using_compacted_format()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int using_compacted_format()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int using_compacted_format()
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
