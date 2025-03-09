# Function: <code>do_execve_file</code>

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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610976,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1880",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610976,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697328,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1880",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697328,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814976,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814976,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887568,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887568,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114464,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1991",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114464,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493363336,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493363336,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226952020,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226952020,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286910032,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286910032,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273084780,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273084780,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581856304,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856304,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793904,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793904,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847616,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847616,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
```

```json
{
  "name": "do_execve_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917136,
      "name": "do_execve_file",
      "external": true,
      "loc": "fs/exec.c:1883",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917136,
      "name": "do_execve_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int do_execve_file(struct file * file, void * __argv, void * __envp)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int do_execve_file(struct file * file, void * __argv, void * __envp)
```
</details>
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
