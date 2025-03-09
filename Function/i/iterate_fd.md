# Function: <code>iterate_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113248,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:960",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113248,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278976,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:966",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278976,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357424,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:966",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357424,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581414208,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:952",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414208,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581555824,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:955",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555824,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581711584,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:961",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711584,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581797904,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:991",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797904,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581916736,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916736,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989120,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989120,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582222864,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1022",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222864,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582270608,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1210",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270608,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582296112,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1221",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296112,
      "name": "iterate_fd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582615008,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1287",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615008,
      "name": "iterate_fd",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583149008,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1289",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149008,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721776,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1299",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721776,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583938800,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1314",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:cgrp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938800,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145440,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:1442",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145440,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493503168,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493503168,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227060212,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227060212,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287066752,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287066752,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273175492,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273175492,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581957856,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957856,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895424,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895424,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581949168,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949168,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int iterate_fd(struct files_struct * files, unsigned int n, int (*)(const void *, struct file *, unsigned int) f, const void * p)
```

```json
{
  "name": "iterate_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020656,
      "name": "iterate_fd",
      "external": true,
      "loc": "fs/file.c:997",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netclassid_cgroup.c:update_classid_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020656,
      "name": "iterate_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
