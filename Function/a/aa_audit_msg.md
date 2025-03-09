# Function: <code>aa_audit_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582477296,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:109",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477296,
      "name": "aa_audit_msg",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582709541,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:109",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709424,
      "name": "aa_audit_msg",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582804133,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:109",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804016,
      "name": "aa_audit_msg",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582893868,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:111",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893760,
      "name": "aa_audit_msg",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583052188,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:111",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052080,
      "name": "aa_audit_msg",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583252826,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:111",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252704,
      "name": "aa_audit_msg",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583370842,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:111",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370720,
      "name": "aa_audit_msg",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583557914,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583557792,
      "name": "aa_audit_msg",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583663642,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663520,
      "name": "aa_audit_msg",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584024522,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024400,
      "name": "aa_audit_msg",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584143962,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:105",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143840,
      "name": "aa_audit_msg",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171119,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:105",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170992,
      "name": "aa_audit_msg",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584555823,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:105",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555696,
      "name": "aa_audit_msg",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585198613,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:148",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198480,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void aa_audit_msg(int type, struct apparmor_audit_data * ad, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585928618,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:148",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928480,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void aa_audit_msg(int type, struct apparmor_audit_data * ad, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161098,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:148",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160960,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void aa_audit_msg(int type, struct apparmor_audit_data * ad, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410350,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:148",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410208,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495456712,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495456520,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228823656,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228823492,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289506892,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289506672,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274645536,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274645370,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583632378,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632256,
      "name": "aa_audit_msg",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569434,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569312,
      "name": "aa_audit_msg",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616154,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616032,
      "name": "aa_audit_msg",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void aa_audit_msg(int type, struct common_audit_data * sa, void (*)(struct audit_buffer *, void *) cb)
```

```json
{
  "name": "aa_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714010,
      "name": "aa_audit_msg",
      "external": true,
      "loc": "security/apparmor/audit.c:107",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit"
      ],
      "caller_func": [
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_check_perms",
        "security/apparmor/lib.c:aa_info_message",
        "security/apparmor/policy.c:audit_policy",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713888,
      "name": "aa_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data * ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data * sa</code>
</li>
</ul>
</details>
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
