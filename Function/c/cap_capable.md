# Function: <code>cap_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, int audit)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582228672,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:71",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:selinux_inode_getsecurity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228672,
      "name": "cap_capable",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, int audit)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447552,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:71",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:selinux_inode_getsecurity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447552,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, int audit)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582539744,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:71",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:selinux_inode_getsecurity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539744,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, int audit)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582624448,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:71",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624448,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, int audit)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582777680,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:71",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777680,
      "name": "cap_capable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, int audit)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978240,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:71",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978240,
      "name": "cap_capable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583089600,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:70",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583089600,
      "name": "cap_capable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583274288,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583274288,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583380384,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380384,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718966,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718400,
      "name": "cap_capable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583839286,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837968,
      "name": "cap_capable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583864998,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863664,
      "name": "cap_capable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584228294,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226912,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584833762,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:66",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred",
        "security/apparmor/policy.c:aa_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832208,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585534514,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:67",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred",
        "security/apparmor/policy.c:aa_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532880,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585766722,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:67",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/policy.c:aa_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596617272,
      "name": "cap_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585765216,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586014290,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:67",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_mmap_addr",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset"
      ],
      "caller_func": [
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/policy.c:aa_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597523154,
      "name": "cap_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586012688,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495129328,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495129328,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228517048,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228517048,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289038848,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289038848,
      "name": "cap_capable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274381620,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274381620,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583349120,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349120,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583286224,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286224,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583332896,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583332896,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int cap_capable(const struct cred * cred, struct user_namespace * targ_ns, int cap, unsigned int opts)
```

```json
{
  "name": "cap_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583427952,
      "name": "cap_capable",
      "external": true,
      "loc": "security/commoncap.c:65",
      "file": "security/commoncap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/commoncap.c:cap_vm_enough_memory",
        "security/commoncap.c:cap_task_prctl",
        "security/commoncap.c:cap_capset",
        "security/selinux/hooks.c:has_cap_mac_admin",
        "security/smack/smack_access.c:smack_privileged_cred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427952,
      "name": "cap_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int opts</code>
</li>
<li>
<b>Param removed. </b>
<code>int audit</code>
</li>
</ul>
</details>
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
