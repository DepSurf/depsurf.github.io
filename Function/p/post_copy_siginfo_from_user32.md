# Function: <code>post_copy_siginfo_from_user32</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541552,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3195",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541552,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562160,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3324",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562160,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588304,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588304,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613824,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3347",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613824,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594048,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3367",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594048,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599616,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3392",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599616,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674608,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3480",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674608,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771232,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3461",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771232,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903232,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3463",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903232,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952960,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3487",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952960,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992256,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3498",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992256,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490752072,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490752072,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283577952,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283577952,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564608,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564608,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493216,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493216,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561888,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561888,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```

```json
{
  "name": "post_copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595376,
      "name": "post_copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3329",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595376,
      "name": "post_copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t * to, const struct compat_siginfo * from)
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
