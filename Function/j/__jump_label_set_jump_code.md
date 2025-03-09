# Function: <code>__jump_label_set_jump_code</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071120,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:__jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071120,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073120,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:__jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073120,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
const void * __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081056,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:31",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081056,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
const void * __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083152,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:31",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083152,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
const void * __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090016,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:31",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090016,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073472,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:__jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073472,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579006368,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:__jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579006368,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073056,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:__jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073056,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```

```json
{
  "name": "__jump_label_set_jump_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077152,
      "name": "__jump_label_set_jump_code",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue",
        "arch/x86/kernel/jump_label.c:__jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077152,
      "name": "__jump_label_set_jump_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>union jump_code_union * code</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, type, code, init</code> ➡️ <code>entry, type, init</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int init</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
const void * __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __jump_label_set_jump_code(struct jump_entry * entry, enum jump_label_type type, union jump_code_union * code, int init)
```
</details>
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
