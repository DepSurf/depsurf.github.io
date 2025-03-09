# Function: <code>ptrace_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429488,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:1777",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429488,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441904,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:1777",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441904,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462272,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:1783",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462272,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450768,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:1805",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450768,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479152,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:1806",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479152,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495344,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:1925",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495344,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528848,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2015",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528848,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553600,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2115",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553600,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579744,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579744,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615104,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_jobctl_trap",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615104,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595376,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2121",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_jobctl_trap",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595376,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601008,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2133",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601008,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676000,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2216",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676000,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784415,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2205",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779568,
      "name": "ptrace_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917103,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2206",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912320,
      "name": "ptrace_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579966913,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2228",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962112,
      "name": "ptrace_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006241,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2219",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001392,
      "name": "ptrace_stop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490742760,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490742760,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224793292,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224793292,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283566800,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283566800,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271448308,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271448308,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556048,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556048,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484752,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484752,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553328,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553328,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586560,
      "name": "ptrace_stop",
      "external": false,
      "loc": "kernel/signal.c:2120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586560,
      "name": "ptrace_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t * info</code> ➡️ <code>kernel_siginfo_t * info</code>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t * info)
```
</details>
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
