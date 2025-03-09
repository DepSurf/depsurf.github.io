# Function: <code>vdso_join_timens</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578868720,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:142",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_on_fork",
        "kernel/time/namespace.c:timens_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868720,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578864544,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:126",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864544,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578864528,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:126",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864528,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866112,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:126",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866112,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578862112,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:126",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578862112,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578864336,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:108",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864336,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578862256,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:111",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578862256,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```

```json
{
  "name": "vdso_join_timens",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872768,
      "name": "vdso_join_timens",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:111",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:timens_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872768,
      "name": "vdso_join_timens",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int vdso_join_timens(struct task_struct * task, struct time_namespace * ns)
```
</details>
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
