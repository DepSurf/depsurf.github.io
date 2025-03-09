# Function: <code>audit_log_lost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028080,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:253",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_skb",
        "kernel/audit.c:audit_printk_skb",
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_n_string",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028080,
      "name": "audit_log_lost",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580060672,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:251",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_send_skb",
        "kernel/audit.c:audit_printk_skb",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060672,
      "name": "audit_log_lost",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100704,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:257",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100704,
      "name": "audit_log_lost",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580106704,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:322",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106704,
      "name": "audit_log_lost",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159376,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:322",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159376,
      "name": "audit_log_lost",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:365",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230768,
      "name": "audit_log_lost.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580219216,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271703,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:361",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283160,
      "name": "audit_log_lost.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580271664,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322600,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333834,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580322560,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371400,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382698,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580371360,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:349",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_buf_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459614,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580445200,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_buf_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315684,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580433712,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257925,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580437600,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162431,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580602240,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:356",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935536,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580806096,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091856,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091856,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183456,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183456,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289632,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289632,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491635904,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491635904,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225588776,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225588776,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284630224,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284630224,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272032414,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272032414,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580340200,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351498,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580340160,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287368,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298666,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580287328,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331448,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342746,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580331408,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void audit_log_lost(const char * message)
```

```json
{
  "name": "audit_log_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580386760,
      "name": "audit_log_lost",
      "external": true,
      "loc": "kernel/audit.c:348",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "kernel/auditsc.c:__audit_log_kern_module",
        "kernel/auditsc.c:audit_alloc",
        "drivers/tty/tty_audit.c:tty_audit_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398026,
      "name": "audit_log_lost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580386720,
      "name": "audit_log_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
