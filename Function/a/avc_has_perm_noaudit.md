# Function: <code>avc_has_perm_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582256512,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1098",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_perm_flags"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256512,
      "name": "avc_has_perm_noaudit.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071582258112,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582477647,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1098",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475296,
      "name": "avc_has_perm_noaudit.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071582476896,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582570111,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1098",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567760,
      "name": "avc_has_perm_noaudit.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071582569360,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582659439,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1098",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657152,
      "name": "avc_has_perm_noaudit.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071582658704,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582814575,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1094",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812288,
      "name": "avc_has_perm_noaudit.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071582813840,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583009141,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1132",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006384,
      "name": "avc_has_perm_noaudit.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071583008336,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583122469,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1132",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119712,
      "name": "avc_has_perm_noaudit.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071583121664,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583309013,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1145",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309601,
      "name": "avc_has_perm_noaudit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583308672,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583414165,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413344,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583754668,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754000,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583876236,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1136",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875536,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583902396,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1137",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901696,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584266124,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1126",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265840,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584879564,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1136",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879184,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585585248,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1136",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585585248,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585816480,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1141",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816480,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586064864,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1142",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_vm_enough_memory",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064864,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495169400,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495168616,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228556212,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228555432,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289106616,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289105600,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274412480,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274411970,
      "name": "avc_has_perm_noaudit",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583382901,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382080,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583319989,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319168,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583366677,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365856,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int avc_has_perm_noaudit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision * avd)
```

```json
{
  "name": "avc_has_perm_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583462076,
      "name": "avc_has_perm_noaudit",
      "external": true,
      "loc": "security/selinux/avc.c:1129",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:cred_has_capability",
        "security/selinux/ss/services.c:security_get_user_sids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461152,
      "name": "avc_has_perm_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
<code>ssid, tsid, tclass, requested, flags, avd</code> ➡️ <code>state, ssid, tsid, tclass, requested, flags, avd</code>
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
<code>state, ssid, tsid, tclass, requested, flags, avd</code> ➡️ <code>ssid, tsid, tclass, requested, flags, avd</code>
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
