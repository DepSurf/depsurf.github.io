# Function: <code>exit_to_usermode_loop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578857856,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:226",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_syscall_32_irqs_off",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857856,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858000,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:141",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858000,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858000,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:134",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858000,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578857632,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:136",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857632,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858864,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:138",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858864,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861312,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:138",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861312,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860640,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:138",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860640,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:135",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:135",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865696,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:219",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__prepare_exit_to_usermode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865696,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:135",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854192,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:135",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854192,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:135",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861664,
      "name": "exit_to_usermode_loop",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```

```json
{
  "name": "exit_to_usermode_loop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861888,
      "name": "exit_to_usermode_loop",
      "external": false,
      "loc": "arch/x86/entry/common.c:135",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861888,
      "name": "exit_to_usermode_loop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
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
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void exit_to_usermode_loop(struct pt_regs * regs, u32 cached_flags)
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
