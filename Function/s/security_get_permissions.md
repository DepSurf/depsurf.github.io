# Function: <code>security_get_permissions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_get_permissions(char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359280,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:2931",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359280,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int security_get_permissions(char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580384,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:2925",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580384,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int security_get_permissions(char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673600,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:2925",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673600,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int security_get_permissions(char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766320,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3041",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766320,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int security_get_permissions(char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922336,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3051",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922336,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3193",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125010,
      "name": "security_get_permissions.cold.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583120912,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3159",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241165,
      "name": "security_get_permissions.cold.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583236960,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3178",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428248,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583423744,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534154,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583529648,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3223",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_perm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883495,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583878960,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_policy * policy, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3353",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_perm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591366979,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583999616,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_policy * policy, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3436",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309958,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071584027360,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int security_get_permissions(struct selinux_policy * policy, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3444",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592301173,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071584397600,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int security_get_permissions(struct selinux_policy * policy, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3447",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594082482,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585023808,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int security_get_permissions(struct selinux_policy * policy, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585741552,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3440",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741552,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int security_get_permissions(struct selinux_policy * policy, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585972208,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3384",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972208,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int security_get_permissions(struct selinux_policy * policy, const char * class, char * * * perms, u32 * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586221216,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3394",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221216,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495298880,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495298880,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228679580,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228679580,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289286160,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289286160,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274519250,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274519250,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502890,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583498384,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439946,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583435440,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486666,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583482160,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int security_get_permissions(struct selinux_state * state, char * class, char * * * perms, int * nperms)
```

```json
{
  "name": "security_get_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_get_permissions",
      "external": true,
      "loc": "security/selinux/ss/services.c:3185",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583030,
      "name": "security_get_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583578352,
      "name": "security_get_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
<code>class, perms, nperms</code> ➡️ <code>state, class, perms, nperms</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy * policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * class</code> ➡️ <code>const char * class</code>
</li>
<li>
<b>Param type changed. </b>
<code>int * nperms</code> ➡️ <code>u32 * nperms</code>
</li>
</ul>
</details>
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
