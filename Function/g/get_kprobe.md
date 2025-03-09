# Function: <code>get_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580076064,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:304",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076064,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110617,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:304",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109344,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150937,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:304",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149664,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580156521,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:336",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155456,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580209417,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:336",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208336,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580269267,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:336",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268352,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580321779,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:336",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320928,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580374339,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373312,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423091,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422064,
      "name": "get_kprobe",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580511160,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:328",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:enable_kprobe",
        "kernel/kprobes.c:__disable_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502320,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499048,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:354",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:enable_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490368,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503112,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:355",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:enable_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494352,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580670728,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:365",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:enable_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661920,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580883924,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:376",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871936,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581173891,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:376",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160416,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581268451,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:376",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253808,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581374739,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:376",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360048,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491690228,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe"
      ],
      "caller_func": [
        "arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491689728,
      "name": "get_kprobe",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225643400,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/arm/probes/kprobes/core.c:kprobe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225642160,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284705448,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/powerpc/kernel/kprobes.c:kprobe_handler",
        "arch/powerpc/kernel/kprobes.c:kprobe_handler",
        "arch/powerpc/kernel/kprobes-ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284703456,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
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
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580391891,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390864,
      "name": "get_kprobe",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580339059,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338032,
      "name": "get_kprobe",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580383139,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382112,
      "name": "get_kprobe",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct kprobe * get_kprobe(void * addr)
```

```json
{
  "name": "get_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580438627,
      "name": "get_kprobe",
      "external": true,
      "loc": "kernel/kprobes.c:323",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__get_valid_kprobe",
        "kernel/kprobes.c:get_optimized_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437616,
      "name": "get_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct kprobe * get_kprobe(void * addr)
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
