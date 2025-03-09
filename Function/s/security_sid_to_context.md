# Function: <code>security_sid_to_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352400,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1302",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352400,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573408,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1296",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573408,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666624,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1296",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666624,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759216,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1308",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759216,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915232,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1313",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915232,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113392,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1350",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113392,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229392,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1347",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229392,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416096,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416096,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522000,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522000,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872224,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1378",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872224,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993072,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1395",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993072,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020000,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1397",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020000,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389456,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1400",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389456,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015376,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1398",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015376,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731504,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1392",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731504,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962320,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1379",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962320,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int security_sid_to_context(u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211168,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1390",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_lsmblob_to_secctx",
        "security/selinux/hooks.c:selinux_lsmblob_to_secctx",
        "security/selinux/hooks.c:selinux_lsm_getattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211168,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495289368,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495289368,
      "name": "security_sid_to_context",
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228671464,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228671464,
      "name": "security_sid_to_context",
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289273664,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289273664,
      "name": "security_sid_to_context",
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274512210,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274512210,
      "name": "security_sid_to_context",
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583490736,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490736,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427808,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427808,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474512,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474512,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int security_sid_to_context(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "security_sid_to_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570672,
      "name": "security_sid_to_context",
      "external": true,
      "loc": "security/selinux/ss/services.c:1337",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/avc.c:avc_audit_post_callback",
        "security/selinux/hooks.c:selinux_key_getsecurity",
        "security/selinux/hooks.c:selinux_secid_to_secctx",
        "security/selinux/hooks.c:selinux_getprocattr",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:show_sid",
        "security/selinux/selinuxfs.c:sel_read_initcon",
        "security/selinux/selinuxfs.c:sel_write_member",
        "security/selinux/selinuxfs.c:sel_write_user",
        "security/selinux/selinuxfs.c:sel_write_relabel",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_context",
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570672,
      "name": "security_sid_to_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<code>sid, scontext, scontext_len</code> ➡️ <code>state, sid, scontext, scontext_len</code>
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
