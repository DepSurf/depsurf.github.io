# Function: <code>slow_avc_audit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256656,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:741",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256656,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475456,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:741",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475456,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567920,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:741",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567920,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657312,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:741",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657312,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812448,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:737",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812448,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006688,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:766",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006688,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120016,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:766",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120016,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a, unsigned int flags)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:758",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309552,
      "name": "slow_avc_audit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583307120,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583411792,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411792,
      "name": "slow_avc_audit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752544,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752544,
      "name": "slow_avc_audit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874064,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:762",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874064,
      "name": "slow_avc_audit",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900224,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:763",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900224,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584264368,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:767",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584264368,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877264,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:769",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877264,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585583296,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:769",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585583296,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814320,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:756",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814320,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062704,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:756",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062704,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495167216,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495167216,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228554032,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228554032,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289103872,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289103872,
      "name": "slow_avc_audit",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274410894,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274410894,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380528,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380528,
      "name": "slow_avc_audit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583317616,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317616,
      "name": "slow_avc_audit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364304,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364304,
      "name": "slow_avc_audit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state * state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data * a)
```

```json
{
  "name": "slow_avc_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583459584,
      "name": "slow_avc_audit",
      "external": true,
      "loc": "security/selinux/avc.c:755",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_has_perm_flags",
        "security/selinux/avc.c:avc_has_perm",
        "security/selinux/avc.c:avc_has_extended_perms",
        "security/selinux/hooks.c:audit_inode_permission",
        "security/selinux/hooks.c:cred_has_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459584,
      "name": "slow_avc_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<code>ssid, tsid, tclass, requested, audited, denied, result, a, flags</code> ➡️ <code>state, ssid, tsid, tclass, requested, audited, denied, result, a, flags</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<code>state, ssid, tsid, tclass, requested, audited, denied, result, a</code> ➡️ <code>ssid, tsid, tclass, requested, audited, denied, result, a</code>
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
