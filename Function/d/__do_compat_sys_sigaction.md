# Function: <code>__do_compat_sys_sigaction</code>

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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510464,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:3758",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510464,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546256,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4085",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546256,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568000,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4333",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568000,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595433,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626976,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4359",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626976,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607376,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4396",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607376,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579614426,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4418",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579690810,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4502",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x64_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788345,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4517",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579922537,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4519",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972537,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4543",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011945,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4554",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490758392,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490758392,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283584448,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283584448,
      "name": "__do_compat_sys_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579571737,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500345,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579569017,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
  "name": "__do_compat_sys_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579602505,
      "name": "__do_compat_sys_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4341",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_sigaction",
        "kernel/signal.c:__ia32_compat_sys_sigaction"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction * act, struct compat_old_sigaction * oact)
```
</details>
</li>
</ul>
