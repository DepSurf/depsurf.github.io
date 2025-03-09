# Function: <code>audit_panic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580027792,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:199",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_secctx",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027792,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580060384,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:197",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060384,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100416,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:203",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100416,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580106432,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:270",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106432,
      "name": "audit_panic",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159104,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:270",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159104,
      "name": "audit_panic",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:313",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230733,
      "name": "audit_panic.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580218960,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271432,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:309",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283125,
      "name": "audit_panic.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580271408,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322329,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333799,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580322304,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371129,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382663,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580371104,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580444969,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:297",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459579,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580444944,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580433465,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:302",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315649,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580433440,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580437353,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:302",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257890,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580437328,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601993,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:302",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162396,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580601968,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593935521,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:304",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935501,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580805792,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091488,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:304",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091488,
      "name": "audit_panic",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581183088,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:304",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183088,
      "name": "audit_panic",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581289264,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:303",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_net_init",
        "kernel/audit.c:audit_log_lost",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:__audit_syscall_entry",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289264,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491635592,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491635592,
      "name": "audit_panic",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225588452,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225588452,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284629808,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284629808,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272032144,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272032144,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580339929,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351463,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580339904,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287097,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298631,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580287072,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331177,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342711,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580331152,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_panic(const char * message)
```

```json
{
  "name": "audit_panic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580386457,
      "name": "audit_panic",
      "external": true,
      "loc": "kernel/audit.c:296",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_net_init",
        "kernel/auditfilter.c:audit_update_lsm_rules",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_watch.c:audit_watch_init",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_fsnotify.c:audit_fsnotify_init",
        "kernel/audit_tree.c:audit_tree_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397991,
      "name": "audit_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580386432,
      "name": "audit_panic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
