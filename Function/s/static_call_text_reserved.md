# Function: <code>static_call_text_reserved</code>

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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179584,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call.c:460",
      "file": "kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179584,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197744,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call.c:462",
      "file": "kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197744,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438096,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call.c:462",
      "file": "kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438096,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777696,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call_inline.c:462",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777696,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202128,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call_inline.c:473",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202128,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402144,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call_inline.c:473",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402144,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int static_call_text_reserved(void * start, void * end)
```

```json
{
  "name": "static_call_text_reserved",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569872,
      "name": "static_call_text_reserved",
      "external": true,
      "loc": "kernel/static_call_inline.c:473",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions",
        "kernel/kprobes.c:check_kprobe_address_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569872,
      "name": "static_call_text_reserved",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int static_call_text_reserved(void * start, void * end)
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
