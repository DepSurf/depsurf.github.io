# Function: <code>do_arch_prctl_common</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579067472,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:609",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:compat_SyS_arch_prctl",
        "arch/x86/kernel/process_64.c:SyS_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067472,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076576,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:641",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:compat_SyS_arch_prctl",
        "arch/x86/kernel/process_64.c:SyS_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076576,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081872,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:786",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081872,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087328,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:850",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087328,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579097024,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:866",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097024,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099008,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:866",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099008,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111504,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:973",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111504,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111344,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:973",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111344,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579117984,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:985",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579117984,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143440,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:1002",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x64_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143440,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(int option, long unsigned int arg2)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181152,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:991",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181152,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
long int do_arch_prctl_common(int option, long unsigned int arg2)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236512,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:1006",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236512,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
long int do_arch_prctl_common(int option, long unsigned int arg2)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579242480,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:1053",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242480,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
long int do_arch_prctl_common(int option, long unsigned int arg2)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271328,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:1065",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271328,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099392,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:866",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099392,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579031824,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:866",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579031824,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098944,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:866",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098944,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```

```json
{
  "name": "do_arch_prctl_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579103392,
      "name": "do_arch_prctl_common",
      "external": true,
      "loc": "arch/x86/kernel/process.c:866",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__x32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_compat_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl",
        "arch/x86/kernel/process_64.c:__x64_sys_arch_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579103392,
      "name": "do_arch_prctl_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int arg2</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int cpuid_enabled</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, option, cpuid_enabled</code> ➡️ <code>option, arg2</code>
</li>
</ul>
</details>
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
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_arch_prctl_common(struct task_struct * task, int option, long unsigned int cpuid_enabled)
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
