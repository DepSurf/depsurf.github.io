# Function: <code>kernel_clone</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512672,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2439",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512672,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515616,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2471",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515616,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 975
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
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587328,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2564",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587328,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678240,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2624",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:user_mode_thread",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678240,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1045
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
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798496,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2649",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:user_mode_thread",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798496,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1080
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
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846640,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2880",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:user_mode_thread",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846640,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1097
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
pid_t kernel_clone(struct kernel_clone_args * args)
```

```json
{
  "name": "kernel_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884432,
      "name": "kernel_clone",
      "external": true,
      "loc": "kernel/fork.c:2870",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone",
        "kernel/fork.c:__do_sys_clone3",
        "kernel/fork.c:__do_sys_clone",
        "kernel/fork.c:__do_sys_vfork",
        "kernel/fork.c:__do_sys_fork",
        "kernel/fork.c:user_mode_thread",
        "kernel/fork.c:kernel_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884432,
      "name": "kernel_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1097
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
pid_t kernel_clone(struct kernel_clone_args * args)
```
</details>
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
