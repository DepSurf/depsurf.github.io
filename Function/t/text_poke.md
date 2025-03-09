# Function: <code>text_poke</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068192,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:689",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068192,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064592,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:690",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064592,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063872,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:695",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063872,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579055616,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:700",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055616,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064624,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:689",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064624,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068576,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:689",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068576,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073184,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:692",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073184,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579083682,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:908",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083568,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085698,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:908",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085584,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579095194,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:963",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097392,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096413,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:975",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098656,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102614,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:896",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105344,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579126534,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:896",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129424,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160953,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1204",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164496,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211188,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1667",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217232,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579216731,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1892",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222672,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246107,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1982",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251536,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579086050,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:908",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085936,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579018482,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:908",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018368,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085634,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:908",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085520,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * text_poke(void * addr, const void * opcode, size_t len)
```

```json
{
  "name": "text_poke",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579089730,
      "name": "text_poke",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:908",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_arm_kprobe",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089616,
      "name": "text_poke",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * text_poke(void * addr, const void * opcode, size_t len)
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
