# Function: <code>release_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030512,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:121",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030512,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026432,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:124",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026432,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026416,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:129",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026416,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018720,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:137",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018720,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579022144,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:135",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579022144,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:143",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029722,
      "name": "release_thread.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579026336,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:143",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034414,
      "name": "release_thread.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579030816,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041934,
      "name": "release_thread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579038480,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040880,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040880,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051280,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:142",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051280,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054096,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:143",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054096,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579060896,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:143",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060896,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082144,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082144,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579110720,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579110720,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579149312,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149312,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151424,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:145",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151424,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180720,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:145",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180720,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490193304,
      "name": "release_thread",
      "external": true,
      "loc": "arch/arm64/kernel/process.c:328",
      "file": "arch/arm64/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490193304,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224417024,
      "name": "release_thread",
      "external": true,
      "loc": "arch/arm/kernel/process.c:220",
      "file": "arch/arm/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224417024,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void release_thread(struct task_struct * t)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282302672,
      "name": "release_thread",
      "external": true,
      "loc": "arch/powerpc/kernel/process.c:1533",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282302672,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "release_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "release_thread",
      "external": false,
      "loc": "arch/riscv/include/asm/processor.h:54",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041232,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041232,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578974192,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974192,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040816,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040816,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void release_thread(struct task_struct * dead_task)
```

```json
{
  "name": "release_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044480,
      "name": "release_thread",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:144",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044480,
      "name": "release_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * dead_task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void release_thread(struct task_struct * dead_task)
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
