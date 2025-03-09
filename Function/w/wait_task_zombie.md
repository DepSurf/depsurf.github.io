# Function: <code>wait_task_zombie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579380826,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:971",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393225,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1057",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579413561,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1047",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401023,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1052",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579429071,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1051",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579444268,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1051",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579477818,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1054",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494880,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1058",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494880,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520880,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520880,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552960,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:978",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552960,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1551
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534208,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:997",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534208,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1560
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537984,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:997",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537984,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610416,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:997",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610416,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703024,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1000",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703024,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828544,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1094",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828544,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877632,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1099",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877632,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916304,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:1075",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916304,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1458
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490659440,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490659440,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224734916,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224734916,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1908
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283483136,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283483136,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1668
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271403996,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271403996,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494544,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494544,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423424,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423424,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1369
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494464,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494464,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
```

```json
{
  "name": "wait_task_zombie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527008,
      "name": "wait_task_zombie",
      "external": false,
      "loc": "kernel/exit.c:974",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527008,
      "name": "wait_task_zombie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
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
int wait_task_zombie(struct wait_opts * wo, struct task_struct * p)
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
