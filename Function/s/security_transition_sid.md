# Function: <code>security_transition_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352624,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1753",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_socket_post_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352624,
      "name": "security_transition_sid",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573632,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1747",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573632,
      "name": "security_transition_sid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666848,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1747",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666848,
      "name": "security_transition_sid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759440,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1759",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759440,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915456,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1762",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915456,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113712,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1823",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113712,
      "name": "security_transition_sid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229712,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1816",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229712,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416464,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416464,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522368,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522368,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872496,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1878",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872496,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993344,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1902",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993344,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020272,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1921",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security_anon",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020272,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1930",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security_anon",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300350,
      "name": "security_transition_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584389728,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015760,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1930",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security_anon",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015760,
      "name": "security_transition_sid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585732000,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1924",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security_anon",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732000,
      "name": "security_transition_sid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962800,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1899",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security_anon",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962800,
      "name": "security_transition_sid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211648,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1909",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security_anon",
        "security/selinux/hooks.c:selinux_bprm_creds_for_exec",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211648,
      "name": "security_transition_sid",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495290048,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495290048,
      "name": "security_transition_sid",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228671864,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228671864,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289274176,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289274176,
      "name": "security_transition_sid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274512784,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274512784,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491104,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491104,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428176,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428176,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474880,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474880,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_transition_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, const struct qstr * qstr, u32 * out_sid)
```

```json
{
  "name": "security_transition_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583571040,
      "name": "security_transition_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:1829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_msg_queue_msgsnd",
        "security/selinux/hooks.c:selinux_socket_post_create",
        "security/selinux/hooks.c:selinux_socket_create",
        "security/selinux/hooks.c:selinux_kernfs_init_security",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:selinux_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571040,
      "name": "security_transition_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<code>ssid, tsid, tclass, qstr, out_sid</code> ➡️ <code>state, ssid, tsid, tclass, qstr, out_sid</code>
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
<code>state, ssid, tsid, tclass, qstr, out_sid</code> ➡️ <code>ssid, tsid, tclass, qstr, out_sid</code>
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
