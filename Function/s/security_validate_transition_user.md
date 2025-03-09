# Function: <code>security_validate_transition_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570400,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:827",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570400,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582663600,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:827",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663600,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756256,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:839",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756256,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912256,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:841",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912256,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110512,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:840",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110512,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226464,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:837",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226464,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583413056,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413056,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518960,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518960,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583869248,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:835",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869248,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990368,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:838",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990368,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016992,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:840",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016992,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:840",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592299849,
      "name": "security_validate_transition_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584386848,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:838",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594081373,
      "name": "security_validate_transition_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585012160,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:832",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096632,
      "name": "security_validate_transition_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585727936,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596619857,
      "name": "security_validate_transition_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585958528,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:829",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525527,
      "name": "security_validate_transition_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586207376,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495285504,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495285504,
      "name": "security_validate_transition_user",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228668132,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228668132,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289269248,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289269248,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274509348,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274509348,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487696,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487696,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424768,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424768,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583471472,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583471472,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int security_validate_transition_user(struct selinux_state * state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```

```json
{
  "name": "security_validate_transition_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567664,
      "name": "security_validate_transition_user",
      "external": true,
      "loc": "security/selinux/ss/services.c:828",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_validatetrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567664,
      "name": "security_validate_transition_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass)
```
</details>
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
<code>oldsid, newsid, tasksid, tclass</code> ➡️ <code>state, oldsid, newsid, tasksid, tclass</code>
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
<code>state, oldsid, newsid, tasksid, tclass</code> ➡️ <code>oldsid, newsid, tasksid, tclass</code>
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
