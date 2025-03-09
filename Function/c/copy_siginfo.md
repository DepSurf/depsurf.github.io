# Function: <code>copy_siginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579415517,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/asm-generic/siginfo.h:24",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424052,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/asm-generic/siginfo.h:24",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal",
        "kernel/signal.c:__send_signal"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579427917,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:35",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440848,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:35",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579447284,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:35",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461216,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:35",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579435141,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:13",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449729,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:13",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579463411,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478131,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579476777,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579493878,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579510421,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536947,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579530028,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561013,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556172,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587148,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579587447,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607605,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:dequeue_synchronous_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579567473,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587812,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:dequeue_synchronous_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579572977,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579609391,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579646945,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685342,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579749910,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783602,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void copy_siginfo(kernel_siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579881573,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886128,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886128,
      "name": "copy_siginfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_siginfo(kernel_siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921920,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    },
    {
      "addr": 18446744071579934336,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921920,
      "name": "copy_siginfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579934336,
      "name": "copy_siginfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_siginfo(kernel_siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961168,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:15",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    },
    {
      "addr": 18446744071579973664,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:15",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961168,
      "name": "copy_siginfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579973664,
      "name": "copy_siginfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490710872,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490751200,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224775784,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3224800040,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283534384,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283576476,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271436484,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271453690,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579532476,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563452,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579461270,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492096,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579529756,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579560732,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563189,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_setsiginfo",
        "kernel/ptrace.c:ptrace_getsiginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594182,
      "name": "copy_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:14",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void copy_siginfo(kernel_siginfo_t * to, const kernel_siginfo_t * from)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
