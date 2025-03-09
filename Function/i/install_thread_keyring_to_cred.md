# Function: <code>install_thread_keyring_to_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202432,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:131",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202432,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419200,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:133",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419200,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511376,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:133",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511376,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582595046,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:136",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592576,
      "name": "install_thread_keyring_to_cred.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071582593168,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582748279,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:138",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745760,
      "name": "install_thread_keyring_to_cred.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071582746368,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582948238,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:138",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945808,
      "name": "install_thread_keyring_to_cred.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071582946432,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583057104,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:138",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054912,
      "name": "install_thread_keyring_to_cred.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583055536,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241095,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238320,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583239488,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583346919,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344144,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583345312,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681765,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679920,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583803269,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801424,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827461,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825616,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584190501,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188656,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584791728,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789552,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585489200,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486896,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585721148,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718368,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585968274,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965488,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495091344,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495088312,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336495089432,
      "name": "install_thread_keyring_to_cred",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228485080,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228481948,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 3228483120,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288992772,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288988432,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 13835058055288989984,
      "name": "install_thread_keyring_to_cred",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274353990,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274351330,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936274352298,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583315655,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312880,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583314048,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583252759,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249984,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583251152,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583299687,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296912,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583298080,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_thread_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_thread_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583394311,
      "name": "install_thread_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:221",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391552,
      "name": "install_thread_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583392720,
      "name": "install_thread_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
