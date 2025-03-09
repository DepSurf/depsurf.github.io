# Function: <code>change_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493968,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:sys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493968,
      "name": "change_pid",
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507952,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507952,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528624,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:420",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528624,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516144,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:421",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516144,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542240,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:290",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542240,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569904,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:302",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569904,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607056,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:310",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607056,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631392,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631392,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656944,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656944,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689312,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:360",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689312,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667504,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:361",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667504,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674320,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:361",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674320,
      "name": "change_pid",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751792,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:361",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751792,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856496,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:361",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856496,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997584,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:361",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997584,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052080,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:364",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052080,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094544,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:364",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094544,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490830632,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__arm64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490830632,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224861452,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224861452,
      "name": "change_pid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283665072,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283665072,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271502032,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271502032,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633264,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633264,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561584,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561584,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630528,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630528,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void change_pid(struct task_struct * task, enum pid_type type, struct pid * pid)
```

```json
{
  "name": "change_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664336,
      "name": "change_pid",
      "external": true,
      "loc": "kernel/pid.c:313",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664336,
      "name": "change_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
