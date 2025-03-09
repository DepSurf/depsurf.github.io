# Function: <code>__getparam_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557285,
      "name": "__getparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3702",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_getattr"
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
  "name": "__getparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579567988,
      "name": "__getparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3955",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_getattr"
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
  "name": "__getparam_dl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579592964,
      "name": "__getparam_dl",
      "external": false,
      "loc": "kernel/sched/core.c:3992",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_getattr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668496,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2514",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668496,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698944,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2501",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698944,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733040,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2586",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733040,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772720,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2589",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772720,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800128,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2580",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800128,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579847968,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847968,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886640,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2626",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886640,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880496,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2753",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880496,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889584,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2737",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889584,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003952,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2750",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003952,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134896,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2900",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134896,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309216,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2900",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309216,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376736,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2926",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376736,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434688,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:3023",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434688,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491037760,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__arm64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491037760,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225047512,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225047512,
      "name": "__getparam_dl",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283916784,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283916784,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271639192,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271639192,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820320,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820320,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754928,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754928,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808336,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808336,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```

```json
{
  "name": "__getparam_dl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853392,
      "name": "__getparam_dl",
      "external": true,
      "loc": "kernel/sched/deadline.c:2627",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853392,
      "name": "__getparam_dl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __getparam_dl(struct task_struct * p, struct sched_attr * attr)
```
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
