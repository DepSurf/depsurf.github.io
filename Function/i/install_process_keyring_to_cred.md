# Function: <code>install_process_keyring_to_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201920,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:174",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201920,
      "name": "install_process_keyring_to_cred.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582202512,
      "name": "install_process_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582421146,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:177",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418640,
      "name": "install_process_keyring_to_cred.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071582419296,
      "name": "install_process_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582513322,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:177",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582510816,
      "name": "install_process_keyring_to_cred.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071582511472,
      "name": "install_process_keyring_to_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582594975,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:183",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592656,
      "name": "install_process_keyring_to_cred.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071582593200,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582748204,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:185",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745840,
      "name": "install_process_keyring_to_cred.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071582746400,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582948148,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:185",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945888,
      "name": "install_process_keyring_to_cred.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071582946464,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583057520,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:185",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054992,
      "name": "install_process_keyring_to_cred.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583055568,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241739,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238400,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583239520,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583347563,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344224,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583345344,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583682098,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680032,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583803602,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801536,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827790,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825728,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584190830,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188768,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584792082,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789680,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585489554,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487040,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585720836,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718512,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585967962,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965632,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495091496,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495088408,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336495089504,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228484876,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228482052,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 3228483168,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288992484,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288988592,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 13835058055288990048,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274353824,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274351416,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936274352356,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583316299,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312960,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583314080,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583253403,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250064,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583251184,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583300331,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296992,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583298112,
      "name": "install_process_keyring_to_cred",
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
int install_process_keyring_to_cred(struct cred * new)
```

```json
{
  "name": "install_process_keyring_to_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583394966,
      "name": "install_process_keyring_to_cred",
      "external": true,
      "loc": "security/keys/process_keys.c:268",
      "file": "security/keys/process_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:lookup_user_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391632,
      "name": "install_process_keyring_to_cred.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583392752,
      "name": "install_process_keyring_to_cred",
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
