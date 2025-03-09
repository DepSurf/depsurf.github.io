# Function: <code>synchronize_sched_expedited_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579784130,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree.c:3770",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_sched_expedited"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579810967,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:409",
      "file": "kernel/rcu/tree.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579837125,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579840129,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:435",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579883969,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:435",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579920207,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:512",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579965000,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:470",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:459",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998976,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071580017166,
      "name": "synchronize_sched_expedited_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 693
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049040,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071580067804,
      "name": "synchronize_sched_expedited_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491258232,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491258232,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225265740,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225265740,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284157296,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284157296,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271779376,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271779376,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1030
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017776,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071580036540,
      "name": "synchronize_sched_expedited_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956896,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071579981944,
      "name": "synchronize_sched_expedited_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009312,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071580028076,
      "name": "synchronize_sched_expedited_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void synchronize_sched_expedited_wait()
```

```json
{
  "name": "synchronize_sched_expedited_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_sched_expedited_wait",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:457",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056592,
      "name": "synchronize_sched_expedited_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071580077953,
      "name": "synchronize_sched_expedited_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
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
void synchronize_sched_expedited_wait()
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void synchronize_sched_expedited_wait()
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
