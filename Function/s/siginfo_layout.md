# Function: <code>siginfo_layout</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum siginfo_layout siginfo_layout(int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488320,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:2674",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32",
        "kernel/signal.c:copy_siginfo_to_user",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488320,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
enum siginfo_layout siginfo_layout(int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579507216,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:2807",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507216,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579541392,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3018",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541392,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579552064,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3147",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552064,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578192,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578192,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579613664,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3170",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613664,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579593888,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3190",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593888,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579599456,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3212",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599456,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579674352,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3297",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674352,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579770960,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3277",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770960,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902944,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3279",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902944,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579952672,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3303",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952672,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991968,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3314",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_external32",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991968,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490741088,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:force_signal_inject",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490741088,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224791692,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224791692,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283564800,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283564800,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271447054,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:send_signal",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271447054,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579554496,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554496,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579483200,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483200,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579551776,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551776,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code)
```

```json
{
  "name": "siginfo_layout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579584912,
      "name": "siginfo_layout",
      "external": true,
      "loc": "kernel/signal.c:3152",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/signalfd.c:signalfd_copyinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584912,
      "name": "siginfo_layout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum siginfo_layout siginfo_layout(int sig, int si_code)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int sig</code> ➡️ <code>unsigned int sig</code>
</li>
</ul>
</details>
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
