# Function: <code>security_bounded_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349456,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:856",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349456,
      "name": "security_bounded_transition",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570496,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:850",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570496,
      "name": "security_bounded_transition",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582663696,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:850",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663696,
      "name": "security_bounded_transition",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756352,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:862",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756352,
      "name": "security_bounded_transition",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912352,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:864",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912352,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:865",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124457,
      "name": "security_bounded_transition.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071583110592,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:862",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240607,
      "name": "security_bounded_transition.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071583226544,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427638,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583413136,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533544,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583519040,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:860",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882911,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583869344,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:863",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591366418,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583990464,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:865",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309364,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584017088,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:866",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592299929,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584387008,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:864",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594081455,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585012368,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:858",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096714,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585728176,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:852",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596619923,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585958752,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int security_bounded_transition(u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:852",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_lsm_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525593,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586207600,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495285760,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495285760,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228668268,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:check_nnp_nosuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228668268,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289269376,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289269376,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274509516,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274509516,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502280,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583487776,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439336,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583424848,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486056,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583471552,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int security_bounded_transition(struct selinux_state * state, u32 old_sid, u32 new_sid)
```

```json
{
  "name": "security_bounded_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_bounded_transition",
      "external": true,
      "loc": "security/selinux/ss/services.c:853",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582420,
      "name": "security_bounded_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583567744,
      "name": "security_bounded_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
<code>old_sid, new_sid</code> ➡️ <code>state, old_sid, new_sid</code>
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
<code>state, old_sid, new_sid</code> ➡️ <code>old_sid, new_sid</code>
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
