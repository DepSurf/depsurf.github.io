# Function: <code>put_compat_rusage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962640,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:511",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:C_SYSC_getrusage",
        "kernel/compat.c:C_SYSC_wait4",
        "kernel/compat.c:C_SYSC_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962640,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993184,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:511",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:C_SYSC_getrusage",
        "kernel/compat.c:C_SYSC_waitid",
        "kernel/compat.c:C_SYSC_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993184,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023680,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:519",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:C_SYSC_getrusage",
        "kernel/compat.c:C_SYSC_waitid",
        "kernel/compat.c:C_SYSC_wait4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023680,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028016,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:304",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:C_SYSC_waitid",
        "kernel/exit.c:C_SYSC_wait4",
        "kernel/sys.c:C_SYSC_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028016,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074832,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:281",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:C_SYSC_waitid",
        "kernel/exit.c:C_SYSC_wait4",
        "kernel/sys.c:C_SYSC_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074832,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134224,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:238",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134224,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181440,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:238",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181440,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226848,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226848,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275056,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275056,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343216,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343216,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328336,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328336,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331616,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331616,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486240,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486240,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680848,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680848,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952112,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952112,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039120,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039120,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136336,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:83",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136336,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491519000,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491519000,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284485632,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284485632,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243856,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243856,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191408,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191408,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235104,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235104,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
```

```json
{
  "name": "put_compat_rusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288096,
      "name": "put_compat_rusage",
      "external": true,
      "loc": "kernel/compat.c:171",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_wait4",
        "kernel/sys.c:__do_compat_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288096,
      "name": "put_compat_rusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
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
int put_compat_rusage(const struct rusage * r, struct compat_rusage * ru)
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
