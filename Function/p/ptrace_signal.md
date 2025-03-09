# Function: <code>ptrace_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579436398,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2082",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448789,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2082",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579469157,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2088",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579457634,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2110",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579485894,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2111",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579503277,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2243",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579537349,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2333",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579561260,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2473",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579587395,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622416,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622416,
      "name": "ptrace_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ptrace_signal(int signr, kernel_siginfo_t * info)
```

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602720,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2479",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602720,
      "name": "ptrace_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579609871,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2491",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579685810,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2573",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info, enum pid_type type)
```

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2558",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782240,
      "name": "ptrace_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071593869745,
      "name": "ptrace_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info, enum pid_type type)
```

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2559",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914944,
      "name": "ptrace_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071595975274,
      "name": "ptrace_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info, enum pid_type type)
```

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2581",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964752,
      "name": "ptrace_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071596492785,
      "name": "ptrace_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info, enum pid_type type)
```

```json
{
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2593",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004080,
      "name": "ptrace_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071597389530,
      "name": "ptrace_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490751268,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224800164,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283576576,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271453764,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563699,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579492331,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579560979,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
  "name": "ptrace_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579594477,
      "name": "ptrace_signal",
      "external": false,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t * info, enum pid_type type)
```
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
