# Function: <code>__pm_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579705638,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:41",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705568,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579733206,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:41",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733136,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729110,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:41",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729040,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761958,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:41",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761888,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579796421,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:70",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796352,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579843029,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:70",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842960,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877061,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:82",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876992,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579927269,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927200,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971285,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971216,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491136360,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491136232,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225133516,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225133416,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284028492,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284028320,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898917,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898848,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579834341,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834272,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887541,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887472,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```

```json
{
  "name": "__pm_notifier_call_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933301,
      "name": "__pm_notifier_call_chain",
      "external": true,
      "loc": "kernel/power/main.c:83",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:pm_notifier_call_chain"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933232,
      "name": "__pm_notifier_call_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
```
</details>
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
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int * nr_calls)
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
