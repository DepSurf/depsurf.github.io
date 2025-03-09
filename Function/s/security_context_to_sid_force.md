# Function: <code>security_context_to_sid_force</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352592,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1506",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352592,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573600,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1500",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573600,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666816,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1500",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666816,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759408,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1512",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759408,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915424,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1515",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915424,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113664,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1564",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113664,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229664,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1557",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229664,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416416,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416416,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522320,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522320,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872464,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1610",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872464,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993312,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1629",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993312,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020240,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1641",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020240,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389696,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1647",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389696,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015712,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1646",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015712,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731936,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1640",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731936,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962736,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1619",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962736,
      "name": "security_context_to_sid_force",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int security_context_to_sid_force(const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211584,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1630",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_lsm_setattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211584,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495289952,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495289952,
      "name": "security_context_to_sid_force",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228671808,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228671808,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289274112,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289274112,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274512702,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274512702,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491056,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491056,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428128,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428128,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474832,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474832,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_context_to_sid_force(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid)
```

```json
{
  "name": "security_context_to_sid_force",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570992,
      "name": "security_context_to_sid_force",
      "external": true,
      "loc": "security/selinux/ss/services.c:1567",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570992,
      "name": "security_context_to_sid_force",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>scontext, scontext_len, sid</code> ➡️ <code>state, scontext, scontext_len, sid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, scontext, scontext_len, sid</code> ➡️ <code>scontext, scontext_len, sid</code>
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
