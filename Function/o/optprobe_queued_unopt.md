# Function: <code>optprobe_queued_unopt</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580425776,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580507167,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:622",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494015,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:645",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580497854,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:646",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580664451,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:656",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:optimize_kprobe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580875519,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:665",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:optimize_kprobe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool optprobe_queued_unopt(struct optimized_kprobe * op)
```

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581164439,
      "name": "optprobe_queued_unopt",
      "external": true,
      "loc": "kernel/kprobes.c:663",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kill_kprobe",
        "kernel/kprobes.c:optimize_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172432,
      "name": "optprobe_queued_unopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool optprobe_queued_unopt(struct optimized_kprobe * op)
```

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581258167,
      "name": "optprobe_queued_unopt",
      "external": true,
      "loc": "kernel/kprobes.c:663",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kill_kprobe",
        "kernel/kprobes.c:optimize_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266864,
      "name": "optprobe_queued_unopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool optprobe_queued_unopt(struct optimized_kprobe * op)
```

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364407,
      "name": "optprobe_queued_unopt",
      "external": true,
      "loc": "kernel/kprobes.c:663",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:kill_kprobe",
        "kernel/kprobes.c:optimize_kprobe"
      ],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373152,
      "name": "optprobe_queued_unopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225646360,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284709544,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580394576,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580341744,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580385824,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optprobe_queued_unopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580441328,
      "name": "optprobe_queued_unopt",
      "external": false,
      "loc": "kernel/kprobes.c:615",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool optprobe_queued_unopt(struct optimized_kprobe * op)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
