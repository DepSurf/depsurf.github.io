# Function: <code>text_poke_queue</code>

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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591166864,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1306",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591166864,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591662416,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1357",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591662416,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591606176,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1278",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591606176,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592779376,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1278",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592779376,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594677216,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1670",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594677216,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596412640,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:2173",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596412640,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596952480,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:2408",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596952480,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
```

```json
{
  "name": "text_poke_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597880000,
      "name": "text_poke_queue",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:2498",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597880000,
      "name": "text_poke_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void text_poke_queue(void * addr, const void * opcode, size_t len, const void * emulate)
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
