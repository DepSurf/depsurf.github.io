# Function: <code>__do_sys_pidfd_send_signal</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579565735,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3705",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579591879,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625104,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3731",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625104,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605392,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3752",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605392,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611520,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3774",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611520,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687568,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3862",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687568,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786256,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3845",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786256,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920336,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3847",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920336,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970240,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3871",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970240,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```

```json
{
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009648,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3882",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009648,
      "name": "__do_sys_pidfd_send_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224803248,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283581464,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271456074,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568183,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579496791,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579565463,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
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
  "name": "__do_sys_pidfd_send_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579598951,
      "name": "__do_sys_pidfd_send_signal",
      "external": false,
      "loc": "kernel/signal.c:3713",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal"
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
long int __do_sys_pidfd_send_signal(int pidfd, int sig, siginfo_t * info, unsigned int flags)
```
</details>
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
