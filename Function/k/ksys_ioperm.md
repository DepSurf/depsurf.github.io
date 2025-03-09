# Function: <code>ksys_ioperm</code>

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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048160,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:26",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048160,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053040,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:26",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053040,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579060736,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:26",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060736,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062864,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:27",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062864,
      "name": "ksys_ioperm",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070880,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070880,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075168,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075168,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082144,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082144,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105104,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105104,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579135616,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135616,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579176928,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176928,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180304,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180304,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209520,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:65",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209520,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063216,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:27",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063216,
      "name": "ksys_ioperm",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578995952,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:27",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995952,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062800,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:27",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062800,
      "name": "ksys_ioperm",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```

```json
{
  "name": "ksys_ioperm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066704,
      "name": "ksys_ioperm",
      "external": true,
      "loc": "arch/x86/kernel/ioport.c:27",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_ioperm",
        "arch/x86/kernel/ioport.c:__x64_sys_ioperm",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066704,
      "name": "ksys_ioperm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int ksys_ioperm(long unsigned int from, long unsigned int num, int turn_on)
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
