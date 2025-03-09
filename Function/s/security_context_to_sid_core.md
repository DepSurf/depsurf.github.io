# Function: <code>security_context_to_sid_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582343840,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1397",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_str_to_sid",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_to_sid_force"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343840,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582564288,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1391",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564288,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582657488,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1391",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657488,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582752320,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1403",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752320,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906880,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1408",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906880,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583105872,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1449",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105872,
      "name": "security_context_to_sid_core.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583220624,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1442",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220624,
      "name": "security_context_to_sid_core.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583405072,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583405072,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583510960,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510960,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863616,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1493",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863616,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983392,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1510",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983392,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013296,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1512",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013296,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1516",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383088,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
    },
    {
      "addr": 18446744071592299516,
      "name": "security_context_to_sid_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1514",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002912,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071594080804,
      "name": "security_context_to_sid_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1508",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725072,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071596096590,
      "name": "security_context_to_sid_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1493",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585955600,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071596619816,
      "name": "security_context_to_sid_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1504",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204448,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071597525486,
      "name": "security_context_to_sid_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495282592,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495282592,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```

```json
{
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228659492,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228659492,
      "name": "security_context_to_sid_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289257808,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289257808,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274504702,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274504702,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583479696,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479696,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416768,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416768,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583463472,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463472,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
  "name": "security_context_to_sid_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583559696,
      "name": "security_context_to_sid_core",
      "external": false,
      "loc": "security/selinux/ss/services.c:1452",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_force",
        "security/selinux/ss/services.c:security_context_to_sid_default",
        "security/selinux/ss/services.c:security_context_str_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559696,
      "name": "security_context_to_sid_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int security_context_to_sid_core(const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
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
<code>state, scontext, scontext_len, sid, def_sid, gfp_flags, force</code> ➡️ <code>scontext, scontext_len, sid, def_sid, gfp_flags, force</code>
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
int security_context_to_sid_core(struct selinux_state * state, const char * scontext, u32 scontext_len, u32 * sid, u32 def_sid, gfp_t gfp_flags, int force)
```
</details>
</li>
</ul>
