# Function: <code>C_SYSC_waitid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo * uinfo, int options, struct compat_rusage * uru)
```

```json
{
  "name": "C_SYSC_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963296,
      "name": "C_SYSC_waitid",
      "external": false,
      "loc": "kernel/compat.c:567",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963296,
      "name": "C_SYSC_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo * uinfo, int options, struct compat_rusage * uru)
```

```json
{
  "name": "C_SYSC_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993824,
      "name": "C_SYSC_waitid",
      "external": false,
      "loc": "kernel/compat.c:567",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993824,
      "name": "C_SYSC_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo * uinfo, int options, struct compat_rusage * uru)
```

```json
{
  "name": "C_SYSC_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580024320,
      "name": "C_SYSC_waitid",
      "external": false,
      "loc": "kernel/compat.c:575",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024320,
      "name": "C_SYSC_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "C_SYSC_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403792,
      "name": "C_SYSC_waitid",
      "external": false,
      "loc": "kernel/exit.c:1718",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:compat_SyS_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403792,
      "name": "C_SYSC_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```

```json
{
  "name": "C_SYSC_waitid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431792,
      "name": "C_SYSC_waitid",
      "external": false,
      "loc": "kernel/exit.c:1715",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:compat_SyS_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431792,
      "name": "C_SYSC_waitid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct compat_siginfo * infop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct compat_siginfo * uinfo</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo * infop, int options, struct compat_rusage * uru)
```
</details>
</li>
</ul>
