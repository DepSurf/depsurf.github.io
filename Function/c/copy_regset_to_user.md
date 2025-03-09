# Function: <code>copy_regset_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579094130,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414848,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_regset"
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
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579094193,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427116,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_regset"
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
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579092290,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446524,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_regset"
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
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579084784,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434503,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:331",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_regset"
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
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579095583,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:368",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462873,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:368",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_regset"
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
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579100425,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:368",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475678,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:368",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579106006,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:368",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509742,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:368",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579116104,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529334,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579118024,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555478,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579130203,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586476,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_regset"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717904,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717904,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725296,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725296,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805328,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805328,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915280,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915280,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069552,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069552,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123424,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123424,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169008,
      "name": "copy_regset_to_user",
      "external": true,
      "loc": "kernel/regset.c:61",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "kernel/ptrace.c:ptrace_regset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169008,
      "name": "copy_regset_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490216264,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490708944,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224422980,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:arch_ptrace",
        "arch/arm/kernel/ptrace.c:arch_ptrace",
        "arch/arm/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 3224777268,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282265328,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:arch_ptrace",
        "arch/powerpc/kernel/ptrace.c:arch_ptrace",
        "arch/powerpc/kernel/ptrace.c:arch_ptrace",
        "arch/powerpc/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282381900,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/powerpc/kernel/ptrace32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283533588,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271436700,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request"
      ],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579118408,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531782,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050424,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460582,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579117960,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529062,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_regset_to_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123048,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562550,
      "name": "copy_regset_to_user",
      "external": false,
      "loc": "include/linux/regset.h:365",
      "file": "kernel/ptrace.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int copy_regset_to_user(struct task_struct * target, const struct user_regset_view * view, unsigned int setno, unsigned int offset, unsigned int size, void * data)
```
</details>
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
