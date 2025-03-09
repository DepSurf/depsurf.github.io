# Function: <code>security_context_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582352464,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1469",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352464,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582573532,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1463",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573472,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582666748,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1463",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666688,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582759340,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1475",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759280,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582915356,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1478",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915296,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583113572,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1523",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113488,
      "name": "security_context_to_sid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583229572,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1516",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229488,
      "name": "security_context_to_sid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416343,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416240,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522247,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522144,
      "name": "security_context_to_sid",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583872404,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1569",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872320,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583993252,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1588",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993168,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584020163,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1600",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020096,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584389619,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1605",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389552,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585015604,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1603",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015520,
      "name": "security_context_to_sid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585731796,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1597",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731696,
      "name": "security_context_to_sid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585962604,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1580",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962512,
      "name": "security_context_to_sid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586211452,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1591",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_lsm_setattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211360,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495289784,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495289632,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228671708,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228671608,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289273984,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289273856,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274512566,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274512438,
      "name": "security_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583490983,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490880,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583428055,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427952,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583474759,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474656,
      "name": "security_context_to_sid",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583570919,
      "name": "security_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1526",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_secctx_to_secid",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570816,
      "name": "security_context_to_sid",
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
<code>scontext, scontext_len, sid, gfp</code> ➡️ <code>state, scontext, scontext_len, sid, gfp</code>
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
<code>state, scontext, scontext_len, sid, gfp</code> ➡️ <code>scontext, scontext_len, sid, gfp</code>
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
