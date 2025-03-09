# Function: <code>arch_set_user_pkey_access</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087616,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:876",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087616,
      "name": "arch_set_user_pkey_access",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085792,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:882",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:SyS_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085792,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077200,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:889",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:SyS_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077200,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085760,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:916",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:SyS_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085760,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579091136,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:916",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579091136,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096384,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:914",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096384,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106784,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:904",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106784,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108608,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:904",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108608,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121792,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:954",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121792,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121968,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:994",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121968,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579128192,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1029",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128192,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:915",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592060295,
      "name": "arch_set_user_pkey_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579154016,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1002",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593826725,
      "name": "arch_set_user_pkey_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579198272,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:997",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595960010,
      "name": "arch_set_user_pkey_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579254736,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1004",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596477336,
      "name": "arch_set_user_pkey_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579261216,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1000",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:__do_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597373121,
      "name": "arch_set_user_pkey_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579291008,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108992,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:904",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108992,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041376,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:904",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041376,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108544,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:904",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108544,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```

```json
{
  "name": "arch_set_user_pkey_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113616,
      "name": "arch_set_user_pkey_access",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:904",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "arch/x86/mm/pkeys.c:__execute_only_pkey",
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113616,
      "name": "arch_set_user_pkey_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_set_user_pkey_access(struct task_struct * tsk, int pkey, long unsigned int init_val)
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
