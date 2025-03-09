# Function: <code>security_context_str_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352496,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1476",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352496,
      "name": "security_context_str_to_sid",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573504,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1470",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573504,
      "name": "security_context_str_to_sid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666720,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1470",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666720,
      "name": "security_context_str_to_sid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759312,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1482",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759312,
      "name": "security_context_str_to_sid",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915328,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1485",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915328,
      "name": "security_context_str_to_sid",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113536,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1531",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113536,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229536,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1524",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229536,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416288,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416288,
      "name": "security_context_str_to_sid",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522192,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522192,
      "name": "security_context_str_to_sid",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872352,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1577",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872352,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993200,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1596",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993200,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020128,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1608",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020128,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389584,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1613",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_sb_mnt_opts_compat",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389584,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015568,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1611",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_add_opt",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015568,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731760,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1605",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_add_opt",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731760,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962576,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1587",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_add_opt",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962576,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int security_context_str_to_sid(const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211424,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1598",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_add_opt",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211424,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495289736,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495289736,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228671660,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228671660,
      "name": "security_context_str_to_sid",
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289273920,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289273920,
      "name": "security_context_str_to_sid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274512522,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274512522,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583490928,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490928,
      "name": "security_context_str_to_sid",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428000,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428000,
      "name": "security_context_str_to_sid",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474704,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474704,
      "name": "security_context_str_to_sid",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state * state, const char * scontext, u32 * sid, gfp_t gfp)
```

```json
{
  "name": "security_context_str_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570864,
      "name": "security_context_str_to_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1534",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:parse_sid",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_access",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570864,
      "name": "security_context_str_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<code>scontext, sid, gfp</code> ➡️ <code>state, scontext, sid, gfp</code>
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
<code>state, scontext, sid, gfp</code> ➡️ <code>scontext, sid, gfp</code>
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
