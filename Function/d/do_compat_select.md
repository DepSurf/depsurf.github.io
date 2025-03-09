# Function: <code>do_compat_select</code>

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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct compat_timeval * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675552,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1258",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675552,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761760,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1270",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761760,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879376,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879376,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951600,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951600,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180640,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1255",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180640,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227888,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1261",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227888,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253920,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1261",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253920,
      "name": "do_compat_select",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571824,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1264",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x64_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x64_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571824,
      "name": "do_compat_select",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101104,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1265",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101104,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669344,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1265",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669344,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886640,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1265",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886640,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584093808,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1265",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584093808,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493447496,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_compat_sys_old_select",
        "fs/select.c:__arm64_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493447496,
      "name": "do_compat_select",
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287003088,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_compat_sys_old_select",
        "fs/select.c:__se_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287003088,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920336,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920336,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857920,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857920,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911648,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911648,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
```

```json
{
  "name": "do_compat_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981280,
      "name": "do_compat_select",
      "external": false,
      "loc": "fs/select.c:1245",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_old_select",
        "fs/select.c:__ia32_compat_sys_old_select",
        "fs/select.c:__x32_compat_sys_select",
        "fs/select.c:__ia32_compat_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981280,
      "name": "do_compat_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct compat_timeval * tvp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct compat_timeval * tvp</code> ➡️ <code>struct old_timeval32 * tvp</code>
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
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
int do_compat_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct old_timeval32 * tvp)
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
