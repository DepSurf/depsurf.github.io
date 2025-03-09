# Function: <code>task_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581469431,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:142",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581653860,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:156",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581742177,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:156",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581796061,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:160",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581945615,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:157",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582130877,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582225357,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:proc_pid_status"
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385056,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385056,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483968,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483968,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582783216,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:151",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582783216,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1263
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582856672,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856672,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582884880,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884880,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218496,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:142",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218496,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583717280,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:144",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583717280,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1354
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584329136,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:147",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329136,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1354
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584559296,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:148",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559296,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1379
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584790656,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:148",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790656,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1382
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494107792,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494107792,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227555972,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227555972,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287775328,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287775328,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273591406,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273591406,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1398
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452704,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452704,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582389872,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389872,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443184,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443184,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
```

```json
{
  "name": "task_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582523392,
      "name": "task_state",
      "external": false,
      "loc": "fs/proc/array.c:152",
      "file": "fs/proc/array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582523392,
      "name": "task_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1373
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
void task_state(struct seq_file * m, struct pid_namespace * ns, struct pid * pid, struct task_struct * p)
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
