# Function: <code>do_compat_sigaltstack</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487088,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3498",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487088,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520560,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3825",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520560,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540208,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4073",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540208,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566288,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566288,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597968,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4099",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597968,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578176,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4136",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578176,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583856,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4158",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583856,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579658048,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4246",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x64_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658048,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755072,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4261",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755072,
      "name": "do_compat_sigaltstack",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887312,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4263",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887312,
      "name": "do_compat_sigaltstack",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936576,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4287",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936576,
      "name": "do_compat_sigaltstack",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975904,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4298",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975904,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490729712,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__arm64_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490729712,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283550464,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__se_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283550464,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542592,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542592,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471344,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471344,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539872,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539872,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```

```json
{
  "name": "do_compat_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573744,
      "name": "do_compat_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4081",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:__x32_compat_sys_sigaltstack",
        "kernel/signal.c:__ia32_compat_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573744,
      "name": "do_compat_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_compat_sigaltstack(const compat_stack_t * uss_ptr, compat_stack_t * uoss_ptr)
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
