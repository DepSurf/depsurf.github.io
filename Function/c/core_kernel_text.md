# Function: <code>core_kernel_text</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579494752,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:69",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494752,
      "name": "core_kernel_text.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579494864,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509189,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:69",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508752,
      "name": "core_kernel_text.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579508864,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579529861,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:69",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529424,
      "name": "core_kernel_text.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579529536,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517493,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:73",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517056,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543637,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:75",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543216,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579571397,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:75",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570960,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608581,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:75",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608144,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632917,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:63",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632480,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658517,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658080,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691285,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:73",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690976,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669557,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:73",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:__kernel_text_address",
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669248,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676485,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:73",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676048,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754533,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:73",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/module.c:symbol_put_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754096,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579860117,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:66",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/module/main.c:symbol_put_addr",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859584,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001509,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:66",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy_locked",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/module/main.c:symbol_put_addr",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000928,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055381,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:66",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy_locked",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/module/main.c:symbol_put_addr",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054800,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097845,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:66",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_set",
        "arch/x86/kernel/alternative.c:text_poke_copy_locked",
        "arch/x86/kernel/alternative.c:__text_poke",
        "kernel/module/main.c:symbol_put_addr",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097264,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490833240,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/arm64/kernel/insn.c:__aarch64_insn_write",
        "arch/arm64/kernel/insn.c:__aarch64_insn_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490832592,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224863516,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/arm/kernel/patch.c:__patch_text_real"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224862904,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283667904,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_call",
        "arch/powerpc/kernel/trace/ftrace.c:ftrace_make_call",
        "arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop",
        "kernel/module.c:symbol_put_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283667056,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271503932,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271503450,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579634837,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634400,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579563141,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562704,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632101,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631664,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int core_kernel_text(long unsigned int addr)
```

```json
{
  "name": "core_kernel_text",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665941,
      "name": "core_kernel_text",
      "external": true,
      "loc": "kernel/extable.c:70",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:func_ptr_is_kernel_text",
        "kernel/extable.c:kernel_text_address",
        "kernel/extable.c:kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665504,
      "name": "core_kernel_text",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
