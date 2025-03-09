# Function: <code>unwind_get_return_address_ptr</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579044655,
      "name": "unwind_get_return_address_ptr",
      "external": false,
      "loc": "arch/x86/include/asm/unwind.h:46",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277834,
      "name": "unwind_get_return_address_ptr",
      "external": false,
      "loc": "arch/x86/include/asm/unwind.h:46",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:unwind_get_return_address"
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
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579037243,
      "name": "unwind_get_return_address_ptr",
      "external": false,
      "loc": "arch/x86/include/asm/unwind.h:54",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274948,
      "name": "unwind_get_return_address_ptr",
      "external": false,
      "loc": "arch/x86/include/asm/unwind.h:54",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293508,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:22",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294416,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579305263,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:22",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306176,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579329802,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:22",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330768,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345096,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346032,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349432,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350368,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379144,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380096,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579377784,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378736,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381400,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382352,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579442904,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444048,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513155,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514336,
      "name": "unwind_get_return_address_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579612563,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613712,
      "name": "unwind_get_return_address_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625171,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626320,
      "name": "unwind_get_return_address_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579654227,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655376,
      "name": "unwind_get_return_address_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345336,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346272,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579277544,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278480,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345256,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346192,
      "name": "unwind_get_return_address_ptr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579353704,
      "name": "unwind_get_return_address_ptr",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:23",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:update_stack_state"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354640,
      "name": "unwind_get_return_address_ptr",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```
</details>
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
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int * unwind_get_return_address_ptr(struct unwind_state * state)
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
