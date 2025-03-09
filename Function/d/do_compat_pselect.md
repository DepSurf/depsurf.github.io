# Function: <code>do_compat_pselect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357660,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/compat.c:1348",
      "file": "fs/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_SyS_pselect6"
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
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581538677,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/compat.c:1351",
      "file": "fs/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_SyS_pselect6"
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
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581624069,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/compat.c:1262",
      "file": "fs/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_SyS_pselect6"
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
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581378839,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1309",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_SyS_pselect6"
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
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581520317,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1300",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_SyS_pselect6"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct compat_timespec * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676128,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1308",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6",
        "fs/select.c:__ia32_compat_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676128,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762336,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1320",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6",
        "fs/select.c:__ia32_compat_sys_pselect6",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762336,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879952,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879952,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952176,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581952176,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181344,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1303",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181344,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228592,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1309",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228592,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254624,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1309",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254624,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582572528,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1312",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x64_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x64_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572528,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101696,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1313",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101696,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669984,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1313",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669984,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887280,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1313",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887280,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094448,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1313",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094448,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493448264,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_compat_sys_pselect6_time32",
        "fs/select.c:__arm64_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493448264,
      "name": "do_compat_pselect",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287003664,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_compat_sys_pselect6_time32",
        "fs/select.c:__se_compat_sys_pselect6_time32",
        "fs/select.c:__se_compat_sys_pselect6_time64",
        "fs/select.c:__se_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287003664,
      "name": "do_compat_pselect",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920912,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920912,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858496,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858496,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912224,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912224,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_compat_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981856,
      "name": "do_compat_pselect",
      "external": false,
      "loc": "fs/select.c:1293",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_pselect6_time32",
        "fs/select.c:__ia32_compat_sys_pselect6_time32",
        "fs/select.c:__x32_compat_sys_pselect6_time64",
        "fs/select.c:__ia32_compat_sys_pselect6_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981856,
      "name": "do_compat_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct compat_timespec * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum poll_time_type type</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct compat_timespec * tsp</code> ➡️ <code>void * tsp</code>
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
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
long int do_compat_pselect(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, void * tsp, compat_sigset_t * sigmask, compat_size_t sigsetsize, enum poll_time_type type)
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
