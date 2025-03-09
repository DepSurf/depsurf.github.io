# Function: <code>security_genfs_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_genfs_sid(const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354896,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2527",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354896,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int security_genfs_sid(const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575920,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2521",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575920,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int security_genfs_sid(const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669136,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2521",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669136,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int security_genfs_sid(const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582761920,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2637",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582761920,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int security_genfs_sid(const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917936,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2647",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917936,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583118160,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2745",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583118160,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234192,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2711",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234192,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420992,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2724",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420992,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526896,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526896,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876688,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2774",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876688,
      "name": "security_genfs_sid",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996496,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2848",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996496,
      "name": "security_genfs_sid",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024000,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2914",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024000,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2924",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300725,
      "name": "security_genfs_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584394016,
      "name": "security_genfs_sid",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int security_genfs_sid(struct selinux_state * state, const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2927",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594082050,
      "name": "security_genfs_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585019936,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_genfs_sid(struct selinux_state * state, const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2920",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596097003,
      "name": "security_genfs_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585737376,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int security_genfs_sid(const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2869",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620189,
      "name": "security_genfs_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585968128,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int security_genfs_sid(const char * fstype, const char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2878",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525859,
      "name": "security_genfs_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586217024,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495295328,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495295328,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228676548,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228676548,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289280976,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289280976,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274516750,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274516750,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583495632,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495632,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583432688,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432688,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583479408,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479408,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int security_genfs_sid(struct selinux_state * state, const char * fstype, char * path, u16 orig_sclass, u32 * sid)
```

```json
{
  "name": "security_genfs_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575584,
      "name": "security_genfs_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2731",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575584,
      "name": "security_genfs_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
<code>fstype, path, orig_sclass, sid</code> ➡️ <code>state, fstype, path, orig_sclass, sid</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * path</code> ➡️ <code>const char * path</code>
</li>
</ul>
</details>
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
<code>state, fstype, path, orig_sclass, sid</code> ➡️ <code>fstype, path, orig_sclass, sid</code>
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
