# Function: <code>find_get_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491344,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:488",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:SyS_waitid",
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitpid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491344,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505264,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:488",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505264,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525936,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:488",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525936,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513616,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:489",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513616,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540976,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540976,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568656,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:383",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568656,
      "name": "find_get_pid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605728,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:390",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605728,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629648,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629648,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655200,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655200,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686384,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:459",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686384,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664832,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:460",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664832,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671776,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:460",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671776,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579749328,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:460",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749328,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858250,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:460",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853888,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999434,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:460",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994816,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048859,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:463",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048640,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091355,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:463",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid_prepare",
        "kernel/exit.c:kernel_waitid_prepare",
        "kernel/sysctl.c:proc_do_cad_pid",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091136,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490828336,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490828336,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224859944,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__se_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859944,
      "name": "find_get_pid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283662576,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__se_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283662576,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271500414,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__se_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271500414,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631520,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631520,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559856,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559856,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628784,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628784,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pid * find_get_pid(pid_t nr)
```

```json
{
  "name": "find_get_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662320,
      "name": "find_get_pid",
      "external": true,
      "loc": "kernel/pid.c:393",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662320,
      "name": "find_get_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
