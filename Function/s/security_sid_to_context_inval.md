# Function: <code>security_sid_to_context_inval</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416192,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416192,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522096,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522096,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872288,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1405",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872288,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993136,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1422",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993136,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020064,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1424",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020064,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389520,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1428",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389520,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015472,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1426",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015472,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731632,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1420",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731632,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int security_sid_to_context_inval(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962448,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1405",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962448,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int security_sid_to_context_inval(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211296,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1416",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211296,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495289544,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495289544,
      "name": "security_sid_to_context_inval",
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228671560,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228671560,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289273792,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289273792,
      "name": "security_sid_to_context_inval",
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274512362,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274512362,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583490832,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490832,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427904,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427904,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474608,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474608,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context_inval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570768,
      "name": "security_sid_to_context_inval",
      "external": true,
      "loc": "security/selinux/ss/services.c:1364",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570768,
      "name": "security_sid_to_context_inval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int security_sid_to_context_inval(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, sid, scontext, scontext_len</code> ➡️ <code>sid, scontext, scontext_len</code>
</li>
</ul>
</details>
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
