# Function: <code>copy_clone_args_from_user</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t size)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579463008,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2541",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone3",
        "kernel/fork.c:__x64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463008,
      "name": "copy_clone_args_from_user",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488496,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone3",
        "kernel/fork.c:__x64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488496,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516576,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2624",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516576,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497776,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2603",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497776,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501568,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2635",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501568,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572240,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2728",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572240,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663408,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2805",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663408,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780560,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2837",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780560,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827296,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:3070",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827296,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865200,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:3060",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__do_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865200,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490622984,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__arm64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490622984,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224701012,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__se_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224701012,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283437600,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__se_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283437600,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271379072,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__se_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271379072,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462160,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone3",
        "kernel/fork.c:__x64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462160,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391120,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone3",
        "kernel/fork.c:__x64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391120,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462080,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone3",
        "kernel/fork.c:__x64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462080,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t usize)
```

```json
{
  "name": "copy_clone_args_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494496,
      "name": "copy_clone_args_from_user",
      "external": false,
      "loc": "kernel/fork.c:2536",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone3",
        "kernel/fork.c:__x64_sys_clone3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494496,
      "name": "copy_clone_args_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int copy_clone_args_from_user(struct kernel_clone_args * kargs, struct clone_args * uargs, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t usize</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
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
