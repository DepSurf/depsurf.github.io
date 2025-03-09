# Function: <code>text_poke_bp_batch</code>

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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083600,
      "name": "text_poke_bp_batch",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1028",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply",
        "arch/x86/kernel/alternative.c:text_poke_bp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083600,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085616,
      "name": "text_poke_bp_batch",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1028",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply",
        "arch/x86/kernel/alternative.c:text_poke_bp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085616,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579095008,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1147",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095008,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096160,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1164",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096160,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579102352,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1085",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579102352,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126272,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1085",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126272,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160624,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1461",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160624,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210832,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:1941",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210832,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216368,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:2166",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216368,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579245744,
      "name": "text_poke_bp_batch",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:2256",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245744,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085968,
      "name": "text_poke_bp_batch",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1028",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply",
        "arch/x86/kernel/alternative.c:text_poke_bp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085968,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018400,
      "name": "text_poke_bp_batch",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1028",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply",
        "arch/x86/kernel/alternative.c:text_poke_bp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018400,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085552,
      "name": "text_poke_bp_batch",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1028",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply",
        "arch/x86/kernel/alternative.c:text_poke_bp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085552,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```

```json
{
  "name": "text_poke_bp_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089648,
      "name": "text_poke_bp_batch",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1028",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply",
        "arch/x86/kernel/alternative.c:text_poke_bp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089648,
      "name": "text_poke_bp_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void text_poke_bp_batch(struct text_poke_loc * tp, unsigned int nr_entries)
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
