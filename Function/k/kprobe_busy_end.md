# Function: <code>kprobe_busy_end</code>

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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503773,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1269",
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
      "addr": 18446744071580513120,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580495572,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1252",
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
      "addr": 18446744071580501104,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499316,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1253",
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
      "addr": 18446744071580505248,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580666932,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1246",
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
      "addr": 18446744071580673024,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882800,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1254",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882800,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172624,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1251",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172624,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267056,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1251",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267056,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void kprobe_busy_end()
```

```json
{
  "name": "kprobe_busy_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373344,
      "name": "kprobe_busy_end",
      "external": true,
      "loc": "kernel/kprobes.c:1251",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373344,
      "name": "kprobe_busy_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void kprobe_busy_end()
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
