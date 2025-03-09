# Function: <code>compat_core_sys_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356288,
      "name": "compat_core_sys_select",
      "external": true,
      "loc": "fs/compat.c:1234",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_old_select",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356288,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537312,
      "name": "compat_core_sys_select",
      "external": true,
      "loc": "fs/compat.c:1237",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_old_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537312,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622704,
      "name": "compat_core_sys_select",
      "external": true,
      "loc": "fs/compat.c:1148",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_old_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622704,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373392,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1195",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_old_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373392,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514880,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1186",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_old_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514880,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672528,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1187",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672528,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758816,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1199",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758816,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876448,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876448,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948704,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948704,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179712,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1184",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179712,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226944,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1190",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226944,
      "name": "compat_core_sys_select",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252944,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1190",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252944,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570848,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1193",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570848,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100128,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1194",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100128,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668352,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1194",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668352,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583885648,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1194",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885648,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092816,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1194",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092816,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493444328,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493444328,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286999328,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286999328,
      "name": "compat_core_sys_select",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917440,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917440,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855024,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855024,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908752,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908752,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
```

```json
{
  "name": "compat_core_sys_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978368,
      "name": "compat_core_sys_select",
      "external": false,
      "loc": "fs/select.c:1174",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978368,
      "name": "compat_core_sys_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * end_time</code> ➡️ <code>struct timespec64 * end_time</code>
</li>
</ul>
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
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
int compat_core_sys_select(int n, compat_ulong_t * inp, compat_ulong_t * outp, compat_ulong_t * exp, struct timespec64 * end_time)
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
