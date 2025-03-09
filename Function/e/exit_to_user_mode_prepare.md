# Function: <code>exit_to_user_mode_prepare</code>

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
void exit_to_user_mode_prepare(struct pt_regs * regs)
```

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138240,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "kernel/entry/common.c:198",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138240,
      "name": "exit_to_user_mode_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void exit_to_user_mode_prepare(struct pt_regs * regs)
```

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143056,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "kernel/entry/common.c:199",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143056,
      "name": "exit_to_user_mode_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void exit_to_user_mode_prepare(struct pt_regs * regs)
```

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286704,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "kernel/entry/common.c:197",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286704,
      "name": "exit_to_user_mode_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void exit_to_user_mode_prepare(struct pt_regs * regs)
```

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460000,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "kernel/entry/common.c:191",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460000,
      "name": "exit_to_user_mode_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void exit_to_user_mode_prepare(struct pt_regs * regs)
```

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707168,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "kernel/entry/common.c:193",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707168,
      "name": "exit_to_user_mode_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void exit_to_user_mode_prepare(struct pt_regs * regs)
```

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784000,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "kernel/entry/common.c:193",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784000,
      "name": "exit_to_user_mode_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "exit_to_user_mode_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597866496,
      "name": "exit_to_user_mode_prepare",
      "external": false,
      "loc": "include/linux/entry-common.h:317",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void exit_to_user_mode_prepare(struct pt_regs * regs)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void exit_to_user_mode_prepare(struct pt_regs * regs)
```
</details>
</li>
</ul>
