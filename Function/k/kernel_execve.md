# Function: <code>kernel_execve</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160976,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1932",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160976,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582185104,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1932",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185104,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502464,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1934",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502464,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025872,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1955",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025872,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589952,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1965",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589952,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583806192,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1972",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583806192,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```

```json
{
  "name": "kernel_execve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012384,
      "name": "kernel_execve",
      "external": true,
      "loc": "fs/exec.c:1993",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:run_init_process",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012384,
      "name": "kernel_execve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int kernel_execve(const char * kernel_filename, const const char * * argv, const const char * * envp)
```
</details>
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
