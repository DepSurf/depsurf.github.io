# Function: <code>__log_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, bool threshold_err, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139280,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:312",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139280,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void __log_error(unsigned int bank, bool deferred_err, bool threshold_err, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139456,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:452",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139456,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void __log_error(unsigned int bank, bool deferred_err, bool threshold_err, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146704,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:758",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146704,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145072,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:744",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145072,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159984,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:741",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159984,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171408,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:793",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171408,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579161280,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:793",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161280,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173376,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:873",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173376,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579175792,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:875",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175792,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197280,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:889",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197280,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192928,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:889",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192928,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198448,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:889",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198448,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234304,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:902",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234304,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579285488,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:725",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285488,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579351008,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:725",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351008,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359888,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:729",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359888,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389760,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:779",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389760,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579176048,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:875",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176048,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111120,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:875",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111120,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579175712,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:875",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175712,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```

```json
{
  "name": "__log_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180896,
      "name": "__log_error",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:875",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180896,
      "name": "__log_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool deferred_err</code>
</li>
<li>
<b>Param reordered. </b>
<code>bank, threshold_err, misc</code> ➡️ <code>bank, deferred_err, threshold_err, misc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 status</code>
</li>
<li>
<b>Param added. </b>
<code>u64 addr</code>
</li>
<li>
<b>Param removed. </b>
<code>bool deferred_err</code>
</li>
<li>
<b>Param removed. </b>
<code>bool threshold_err</code>
</li>
</ul>
</details>
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc)
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
