# Function: <code>__blocking_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506432,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:blocking_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506432,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520544,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:blocking_notifier_call_chain",
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520544,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544192,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:blocking_notifier_call_chain",
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544192,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531296,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531296,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557792,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557792,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579586064,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586064,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579623264,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:304",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623264,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579648032,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648032,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685168,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685168,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579724640,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:271",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724640,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490860464,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490860464,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224880348,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224880348,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283691024,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283691024,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271518836,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271518836,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661488,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661488,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579589840,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589840,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658752,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658752,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__blocking_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692736,
      "name": "__blocking_notifier_call_chain",
      "external": true,
      "loc": "kernel/notifier.c:306",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692736,
      "name": "__blocking_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head * nh, long unsigned int val, void * v, int nr_to_call, int * nr_calls)
```
</details>
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
