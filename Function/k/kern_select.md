# Function: <code>kern_select</code>

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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679120,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:673",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679120,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765776,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:698",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765776,
      "name": "kern_select",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883040,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883040,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955408,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955408,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187648,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187648,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235104,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235104,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260944,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260944,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582578832,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:703",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582578832,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107568,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:704",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107568,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583676112,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:704",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583676112,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583893856,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:704",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893856,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct __kernel_old_timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101024,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:704",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101024,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493451592,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__arm64_sys_select"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227018280,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_old_select",
        "fs/select.c:__se_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227018280,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287006832,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__se_sys_select"
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
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273135562,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__se_sys_select"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924144,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924144,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861728,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861728,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915456,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915456,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```

```json
{
  "name": "kern_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581985088,
      "name": "kern_select",
      "external": false,
      "loc": "fs/select.c:700",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_select",
        "fs/select.c:__x64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985088,
      "name": "kern_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timeval * tvp</code> ➡️ <code>struct __kernel_old_timeval * tvp</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kern_select(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timeval * tvp)
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
