# Function: <code>collect_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583119317,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:6",
      "file": "lib/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
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
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583413477,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:6",
      "file": "lib/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int collect_syscall(struct task_struct * target, long int * callno, long unsigned int * args, unsigned int maxargs, long unsigned int * sp, long unsigned int * pc)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539056,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:6",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539056,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int collect_syscall(struct task_struct * target, long int * callno, long unsigned int * args, unsigned int maxargs, long unsigned int * sp, long unsigned int * pc)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576704,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:7",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576704,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int collect_syscall(struct task_struct * target, long int * callno, long unsigned int * args, unsigned int maxargs, long unsigned int * sp, long unsigned int * pc)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822528,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822528,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int collect_syscall(struct task_struct * target, long int * callno, long unsigned int * args, unsigned int maxargs, long unsigned int * sp, long unsigned int * pc)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584023328,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023328,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int collect_syscall(struct task_struct * target, long int * callno, long unsigned int * args, unsigned int maxargs, long unsigned int * sp, long unsigned int * pc)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105024,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105024,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293792,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293792,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584428512,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428512,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990640,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990640,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585112624,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112624,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584992784,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584992784,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585433456,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433456,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573216,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573216,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808448,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808448,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588079920,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079920,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588415248,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588415248,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496313624,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496313624,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229648432,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229648432,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290626208,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290626208,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275367238,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275367238,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397248,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397248,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332448,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332448,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584380160,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380160,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int collect_syscall(struct task_struct * target, struct syscall_info * info)
```

```json
{
  "name": "collect_syscall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486224,
      "name": "collect_syscall",
      "external": false,
      "loc": "lib/syscall.c:8",
      "file": "lib/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/syscall.c:task_current_syscall",
        "lib/syscall.c:task_current_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486224,
      "name": "collect_syscall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int collect_syscall(struct task_struct * target, long int * callno, long unsigned int * args, unsigned int maxargs, long unsigned int * sp, long unsigned int * pc)
```
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct syscall_info * info</code>
</li>
<li>
<b>Param removed. </b>
<code>long int * callno</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * args</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int maxargs</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * sp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * pc</code>
</li>
</ul>
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
