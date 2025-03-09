# Function: <code>poll_select_finish</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__do_sys_pselect6",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873360,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071581883816,
      "name": "poll_select_finish.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945696,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945696,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176704,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176704,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224048,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224048,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582250096,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582250096,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567936,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x64_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x64_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567936,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097104,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:298",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097104,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665264,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:298",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665264,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882496,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:298",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882496,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089664,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:298",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089664,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493441592,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_compat_sys_ppoll_time64",
        "fs/select.c:__arm64_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__arm64_sys_ppoll",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/select.c:__arm64_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493441592,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227012460,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll_time32",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:do_pselect",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227012460,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286995776,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_compat_sys_ppoll_time64",
        "fs/select.c:__se_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_pselect6",
        "fs/select.c:__se_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286995776,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273131628,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_pselect6",
        "fs/select.c:__se_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273131628,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581914432,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914432,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852016,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852016,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905744,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905744,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```

```json
{
  "name": "poll_select_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975360,
      "name": "poll_select_finish",
      "external": false,
      "loc": "fs/select.c:297",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975360,
      "name": "poll_select_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int poll_select_finish(struct timespec64 * end_time, void * p, enum poll_time_type pt_type, int ret)
```
</details>
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
