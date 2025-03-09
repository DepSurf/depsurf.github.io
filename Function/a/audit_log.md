# Function: <code>audit_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031664,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2006",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_init",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_validate_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031664,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064240,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2027",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064240,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104464,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2146",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104464,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109824,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2325",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109824,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162384,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2333",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162384,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222160,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2375",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222160,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274576,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2372",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274576,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325552,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2337",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325552,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374352,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374352,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449792,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2491",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/hooks.c:selinux_lockdown",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_validtrans_handle_fail",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449792,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438384,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2508",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/hooks.c:selinux_lockdown",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_validtrans_handle_fail",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438384,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442112,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2508",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/hooks.c:selinux_lockdown",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442112,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580606960,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2547",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_ntp_log",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/hooks.c:selinux_lockdown",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606960,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811472,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2599",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811472,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097536,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2597",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097536,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189152,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2597",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_fanotify",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189152,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295360,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2619",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:__audit_fanotify",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295360,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491639592,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491639592,
      "name": "audit_log",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225592068,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225592068,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284634864,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284634864,
      "name": "audit_log",
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272035344,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272035344,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343152,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343152,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290320,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290320,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580334400,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334400,
      "name": "audit_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void audit_log(struct audit_context * ctx, gfp_t gfp_mask, int type, const char * fmt, void (anon))
```

```json
{
  "name": "audit_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389648,
      "name": "audit_log",
      "external": true,
      "loc": "kernel/audit.c:2339",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_init",
        "kernel/auditsc.c:audit_log_ntp_val",
        "kernel/auditsc.c:__audit_tk_injoffset",
        "kernel/auditsc.c:__audit_fanotify",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_bounded_transition",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389648,
      "name": "audit_log",
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
