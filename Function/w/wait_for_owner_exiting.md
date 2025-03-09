# Function: <code>wait_for_owner_exiting</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580198128,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198128,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580266512,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1131",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266512,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580250416,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1128",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250416,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580255584,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1128",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255584,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580406896,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1186",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406896,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627328,
      "name": "wait_for_owner_exiting",
      "external": true,
      "loc": "kernel/futex/core.c:469",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627328,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893328,
      "name": "wait_for_owner_exiting",
      "external": true,
      "loc": "kernel/futex/core.c:469",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893328,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977184,
      "name": "wait_for_owner_exiting",
      "external": true,
      "loc": "kernel/futex/core.c:469",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977184,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071024,
      "name": "wait_for_owner_exiting",
      "external": true,
      "loc": "kernel/futex/core.c:482",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071024,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491428112,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491428112,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225424568,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225424568,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284377664,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284377664,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271893902,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271893902,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580166928,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166928,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580114544,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114544,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580158400,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158400,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```

```json
{
  "name": "wait_for_owner_exiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580212256,
      "name": "wait_for_owner_exiting",
      "external": false,
      "loc": "kernel/futex.c:1202",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212256,
      "name": "wait_for_owner_exiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct * exiting)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
