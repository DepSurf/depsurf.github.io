# Function: <code>kprobe_busy_begin</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503540,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1259",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kprobe_flush_task"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513072,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580495411,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1242",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kprobe_flush_task"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501056,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499155,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1243",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kprobe_flush_task"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505200,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580666771,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1236",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kprobe_flush_task"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672976,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882736,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1244",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882736,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172544,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1241",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172544,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266976,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1241",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266976,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kprobe_busy_begin()
```

```json
{
  "name": "kprobe_busy_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373264,
      "name": "kprobe_busy_begin",
      "external": true,
      "loc": "kernel/kprobes.c:1241",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373264,
      "name": "kprobe_busy_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void kprobe_busy_begin()
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
