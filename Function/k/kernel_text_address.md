# Function: <code>kernel_text_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495088,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/kprobes.c:init_kprobes",
        "kernel/jump_label.c:__jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495088,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509088,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/kprobes.c:init_kprobes",
        "kernel/jump_label.c:__jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509088,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529760,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/kprobes.c:init_kprobes",
        "kernel/jump_label.c:__jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529760,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517344,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:128",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/kprobes.c:init_kprobes",
        "kernel/jump_label.c:__jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517344,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543328,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:122",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:init_kprobes",
        "kernel/jump_label.c:__jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543328,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571072,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:122",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:init_kprobes",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571072,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608256,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:122",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608256,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579632592,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:110",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632592,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579658192,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658192,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691093,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/kprobes.c:check_kprobe_address_safe",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690560,
      "name": "kernel_text_address.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071579691200,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669365,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/extable.c:__kernel_text_address"
      ],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/kprobes.c:check_kprobe_address_safe",
        "kernel/static_call.c:static_call_add_module",
        "kernel/static_call.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668832,
      "name": "kernel_text_address.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071579669472,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676160,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/static_call.c:static_call_module_notify",
        "kernel/static_call.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676160,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754208,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:120",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/static_call.c:static_call_module_notify",
        "kernel/static_call.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754208,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579859696,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:94",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859696,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001056,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:94",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/utils.c:get_branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001056,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054928,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:94",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/utils.c:get_branch_type",
        "arch/x86/kernel/static_call.c:__static_call_fixup",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054928,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097392,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:94",
      "file": "kernel/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/utils.c:get_branch_type",
        "arch/x86/kernel/static_call.c:__static_call_fixup",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:__static_call_update",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097392,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490832784,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/alternative.c:patch_alternative",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490832784,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224863092,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224863092,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283667264,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/callchain.c:perf_callchain_kernel",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283667264,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271503594,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/extable.c:__kernel_text_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271503594,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634512,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634512,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562816,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562816,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631776,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631776,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int kernel_text_address(long unsigned int addr)
```

```json
{
  "name": "kernel_text_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665616,
      "name": "kernel_text_address",
      "external": true,
      "loc": "kernel/extable.c:117",
      "file": "kernel/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/extable.c:__kernel_text_address",
        "kernel/kprobes.c:kprobe_add_ksym_blacklist",
        "kernel/jump_label.c:__jump_label_update",
        "lib/error-inject.c:populate_error_injection_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665616,
      "name": "kernel_text_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
