# Function: <code>rethook_recycle</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rethook_recycle(struct rethook_node * node)
```

```json
{
  "name": "rethook_recycle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581372401,
      "name": "rethook_recycle",
      "external": true,
      "loc": "kernel/trace/rethook.c:128",
      "file": "kernel/trace/rethook.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rethook.c:rethook_flush_task",
        "kernel/trace/rethook.c:rethook_flush_task"
      ],
      "caller_func": [
        "kernel/kprobes.c:pre_handler_kretprobe",
        "kernel/trace/rethook.c:rethook_trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372208,
      "name": "rethook_recycle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rethook_recycle(struct rethook_node * node)
```

```json
{
  "name": "rethook_recycle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581709073,
      "name": "rethook_recycle",
      "external": true,
      "loc": "kernel/trace/rethook.c:130",
      "file": "kernel/trace/rethook.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rethook.c:rethook_flush_task",
        "kernel/trace/rethook.c:rethook_flush_task"
      ],
      "caller_func": [
        "kernel/kprobes.c:pre_handler_kretprobe",
        "kernel/trace/rethook.c:rethook_trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708864,
      "name": "rethook_recycle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rethook_recycle(struct rethook_node * node)
```

```json
{
  "name": "rethook_recycle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581855509,
      "name": "rethook_recycle",
      "external": true,
      "loc": "kernel/trace/rethook.c:143",
      "file": "kernel/trace/rethook.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rethook.c:rethook_flush_task",
        "kernel/trace/rethook.c:rethook_flush_task"
      ],
      "caller_func": [
        "kernel/kprobes.c:pre_handler_kretprobe",
        "kernel/trace/rethook.c:rethook_trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855296,
      "name": "rethook_recycle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rethook_recycle(struct rethook_node * node)
```

```json
{
  "name": "rethook_recycle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581979002,
      "name": "rethook_recycle",
      "external": true,
      "loc": "kernel/trace/rethook.c:142",
      "file": "kernel/trace/rethook.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rethook.c:rethook_trampoline_handler",
        "kernel/trace/rethook.c:rethook_trampoline_handler",
        "kernel/trace/rethook.c:rethook_flush_task",
        "kernel/trace/rethook.c:rethook_flush_task"
      ],
      "caller_func": [
        "kernel/kprobes.c:pre_handler_kretprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977936,
      "name": "rethook_recycle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void rethook_recycle(struct rethook_node * node)
```
</details>
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
