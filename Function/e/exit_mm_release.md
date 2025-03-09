# Function: <code>exit_mm_release</code>

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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493984,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493984,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524400,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1340",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524400,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506448,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1337",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506448,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509904,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1343",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509904,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581328,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1422",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581328,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672112,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1493",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672112,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792496,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1516",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792496,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840400,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1657",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840400,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878208,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1653",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878208,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490628288,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490628288,
      "name": "exit_mm_release",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224705372,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224705372,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283445680,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283445680,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271389046,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271389046,
      "name": "exit_mm_release",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467648,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467648,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396576,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396576,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467568,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467568,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "exit_mm_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499312,
      "name": "exit_mm_release",
      "external": true,
      "loc": "kernel/fork.c:1326",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499312,
      "name": "exit_mm_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void exit_mm_release(struct task_struct * tsk, struct mm_struct * mm)
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
