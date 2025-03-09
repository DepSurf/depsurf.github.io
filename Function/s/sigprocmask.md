# Function: <code>sigprocmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437984,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2501",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigprocmask",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/fuse/dev.c:request_wait_answer",
        "fs/fuse/dev.c:request_wait_answer",
        "fs/fuse/dev.c:request_wait_answer",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dev.c:__fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437984,
      "name": "sigprocmask",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450448,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2501",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigprocmask",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450448,
      "name": "sigprocmask",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470896,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2514",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigprocmask",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470896,
      "name": "sigprocmask",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459264,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2535",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigprocmask",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459264,
      "name": "sigprocmask",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487504,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2536",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigprocmask",
        "kernel/signal.c:SyS_rt_sigprocmask",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487504,
      "name": "sigprocmask",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505968,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2669",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:do_pselect",
        "fs/select.c:do_pselect",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505968,
      "name": "sigprocmask",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540144,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2768",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540144,
      "name": "sigprocmask",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550496,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2927",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550496,
      "name": "sigprocmask",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576624,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576624,
      "name": "sigprocmask",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612096,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2950",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612096,
      "name": "sigprocmask",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592320,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2970",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592320,
      "name": "sigprocmask",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588960,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2992",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588960,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664224,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:3077",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664224,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759104,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:3057",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759104,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890976,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:3059",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890976,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940208,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:3083",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940208,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979552,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:3094",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979552,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490739672,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_sigset_deactivate",
        "virt/kvm/kvm_main.c:kvm_sigset_activate",
        "kernel/signal.c:__arm64_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__arm64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490739672,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224790556,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224790556,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283563344,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__se_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283563344,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271446418,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271446418,
      "name": "sigprocmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552928,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552928,
      "name": "sigprocmask",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481632,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481632,
      "name": "sigprocmask",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550208,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550208,
      "name": "sigprocmask",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int sigprocmask(int how, sigset_t * set, sigset_t * oldset)
```

```json
{
  "name": "sigprocmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583344,
      "name": "sigprocmask",
      "external": true,
      "loc": "kernel/signal.c:2932",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_sys_rt_sigprocmask",
        "kernel/signal.c:__x64_sys_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583344,
      "name": "sigprocmask",
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
