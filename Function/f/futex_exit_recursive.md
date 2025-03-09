# Function: <code>futex_exit_recursive</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212592,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212592,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280128,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3707",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280128,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263344,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3631",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263344,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268336,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3628",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268336,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580419968,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3859",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419968,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627952,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex/core.c:1042",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:make_task_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627952,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894064,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex/core.c:1050",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:make_task_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894064,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977920,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex/core.c:1050",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:make_task_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977920,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071776,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex/core.c:1075",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:make_task_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071776,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491450160,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491450160,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225436824,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225436824,
      "name": "futex_exit_recursive",
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284399888,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284399888,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271908956,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271908956,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181392,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181392,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128912,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128912,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172864,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172864,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void futex_exit_recursive(struct task_struct * tsk)
```

```json
{
  "name": "futex_exit_recursive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224960,
      "name": "futex_exit_recursive",
      "external": true,
      "loc": "kernel/futex.c:3794",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224960,
      "name": "futex_exit_recursive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void futex_exit_recursive(struct task_struct * tsk)
```
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
