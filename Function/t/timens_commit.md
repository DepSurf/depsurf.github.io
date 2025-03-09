# Function: <code>timens_commit</code>

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
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246400,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:280",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246400,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251520,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:280",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251520,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:280",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592157905,
      "name": "timens_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071580402640,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:280",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593932882,
      "name": "timens_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580621712,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:298",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595998994,
      "name": "timens_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580887440,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:298",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517124,
      "name": "timens_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580971280,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
```

```json
{
  "name": "timens_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timens_commit",
      "external": true,
      "loc": "kernel/time/namespace.c:298",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/namespace.c:timens_on_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597417076,
      "name": "timens_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581066016,
      "name": "timens_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void timens_commit(struct task_struct * tsk, struct time_namespace * ns)
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
