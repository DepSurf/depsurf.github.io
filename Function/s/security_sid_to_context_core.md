# Function: <code>security_sid_to_context_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582340192,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1242",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context",
        "security/selinux/ss/services.c:security_sid_to_context_force"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340192,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582561248,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1236",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561248,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582654448,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1236",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654448,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747024,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1248",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747024,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903040,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1253",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903040,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1284",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100976,
      "name": "security_sid_to_context_core.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071583123902,
      "name": "security_sid_to_context_core.isra.15.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1281",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216960,
      "name": "security_sid_to_context_core.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071583240094,
      "name": "security_sid_to_context_core.isra.15.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406800,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071583427138,
      "name": "security_sid_to_context_core.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512688,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071583533042,
      "name": "security_sid_to_context_core.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1308",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865952,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071583882661,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1323",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981040,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071591365913,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1325",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584007552,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071591308890,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1327",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382752,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071592299413,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1325",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002016,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071594080701,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1319",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718048,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071596096444,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1308",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948432,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071596619680,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1308",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200256,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071597525371,
      "name": "security_sid_to_context_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495283192,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495283192,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228661244,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228661244,
      "name": "security_sid_to_context_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289260496,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289260496,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274501402,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274501402,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583481424,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071583501778,
      "name": "security_sid_to_context_core.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418496,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071583438834,
      "name": "security_sid_to_context_core.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465200,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071583485554,
      "name": "security_sid_to_context_core.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_sid_to_context_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_to_context_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1267",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_inval",
        "security/selinux/ss/services.c:security_sid_to_context_force",
        "security/selinux/ss/services.c:security_sid_to_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561408,
      "name": "security_sid_to_context_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071583581916,
      "name": "security_sid_to_context_core.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int security_sid_to_context_core(u32 sid, char * * scontext, u32 * scontext_len, int force)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```
</details>
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
<code>state, sid, scontext, scontext_len, force, only_invalid</code> ➡️ <code>sid, scontext, scontext_len, force, only_invalid</code>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int security_sid_to_context_core(struct selinux_state * state, u32 sid, char * * scontext, u32 * scontext_len, int force, int only_invalid)
```
</details>
</li>
</ul>
