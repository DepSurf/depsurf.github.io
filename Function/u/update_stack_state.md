# Function: <code>update_stack_state</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state * state, void * addr, size_t len)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277920,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:136",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277920,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274656,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:196",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274656,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293216,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:206",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293216,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305040,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:206",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305040,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329568,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:206",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329568,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344864,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:192",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344864,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579349200,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:192",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349200,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378912,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:186",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378912,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377552,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:186",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377552,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381168,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:186",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381168,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442672,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:186",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442672,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512912,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:186",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512912,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612320,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:196",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612320,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624928,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:196",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624928,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653984,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:196",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653984,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345104,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:192",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345104,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277312,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:192",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277312,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345024,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:192",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345024,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```

```json
{
  "name": "update_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579353472,
      "name": "update_stack_state",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:192",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:__unwind_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353472,
      "name": "update_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool update_stack_state(struct unwind_state * state, void * addr, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int * next_bp</code>
</li>
<li>
<b>Param removed. </b>
<code>void * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool update_stack_state(struct unwind_state * state, long unsigned int * next_bp)
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
