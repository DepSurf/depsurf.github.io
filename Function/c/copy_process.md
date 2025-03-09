# Function: <code>copy_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * copy_process(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int * child_tidptr, struct pid * pid, int trace, long unsigned int tls)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579362800,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1248",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:fork_idle",
        "kernel/fork.c:_do_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362800,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6855
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579377606,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1304",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370224,
      "name": "copy_process.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7021
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396646,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1460",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389008,
      "name": "copy_process.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579383670,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1528",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376432,
      "name": "copy_process.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6865
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410518,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1539",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403264,
      "name": "copy_process.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6890
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579424895,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1610",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418960,
      "name": "copy_process.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579458319,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1680",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449872,
      "name": "copy_process.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8119
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579468080,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1775",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579468080,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7051
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494144,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494144,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7014
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524592,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1847",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524592,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4948
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506640,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1858",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506640,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5710
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510096,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1857",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:create_io_thread",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510096,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5326
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581520,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1936",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:create_io_thread",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581520,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5612
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672336,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1981",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:create_io_thread",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672336,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5649
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792768,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:2015",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:create_io_thread",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792768,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5486
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840832,
      "name": "copy_process",
      "external": true,
      "loc": "kernel/fork.c:2248",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:create_io_thread",
        "kernel/fork.c:fork_idle",
        "kernel/vhost_task.c:vhost_task_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840832,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5647
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878640,
      "name": "copy_process",
      "external": true,
      "loc": "kernel/fork.c:2245",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:create_io_thread",
        "kernel/fork.c:fork_idle",
        "kernel/vhost_task.c:vhost_task_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878640,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5619
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490628504,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490628504,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5396
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224705540,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224705540,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6200
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283445968,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283445968,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6628
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271383496,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271383496,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4954
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467808,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467808,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7014
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396736,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396736,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6984
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467728,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467728,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7014
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
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
```

```json
{
  "name": "copy_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499472,
      "name": "copy_process",
      "external": false,
      "loc": "kernel/fork.c:1766",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:fork_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499472,
      "name": "copy_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7090
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct task_struct * copy_process(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stack_size, int * child_tidptr, struct pid * pid, int trace, long unsigned int tls)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct task_struct * copy_process(struct pid * pid, int trace, int node, struct kernel_clone_args * args)
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
