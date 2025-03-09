# Function: <code>futex_exec_release</code>

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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212656,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212656,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280208,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3755",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280208,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263424,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3679",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263424,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268416,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3676",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268416,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420048,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3907",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420048,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628032,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex/core.c:1090",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628032,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894160,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex/core.c:1098",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894160,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978016,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex/core.c:1098",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978016,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071872,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex/core.c:1123",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071872,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491450248,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491450248,
      "name": "futex_exec_release",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225436888,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225436888,
      "name": "futex_exec_release",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284400000,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284400000,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271909030,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271909030,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181456,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181456,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128976,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128976,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172928,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172928,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void futex_exec_release(struct task_struct * tsk)
```

```json
{
  "name": "futex_exec_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225024,
      "name": "futex_exec_release",
      "external": true,
      "loc": "kernel/futex.c:3842",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exec_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225024,
      "name": "futex_exec_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void futex_exec_release(struct task_struct * tsk)
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
