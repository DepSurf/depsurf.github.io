# Function: <code>__audit_log_kern_module</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143088,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2384",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:SyS_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143088,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195696,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2407",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:SyS_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195696,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255344,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2414",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255344,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308592,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2399",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308592,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360464,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360464,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409280,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409280,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580487792,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2555",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487792,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476048,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2572",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476048,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480016,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2570",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480016,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647664,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2588",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647664,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856416,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2870",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856416,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143984,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2848",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143984,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237072,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2847",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237072,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343152,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2837",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343152,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491674624,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__arm64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491674624,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225629052,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__se_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225629052,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284684048,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__se_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284684048,
      "name": "__audit_log_kern_module",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272065052,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__se_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272065052,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378080,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378080,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325248,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325248,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369328,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369328,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __audit_log_kern_module(char * name)
```

```json
{
  "name": "__audit_log_kern_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424848,
      "name": "__audit_log_kern_module",
      "external": true,
      "loc": "kernel/auditsc.c:2503",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424848,
      "name": "__audit_log_kern_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __audit_log_kern_module(char * name)
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
