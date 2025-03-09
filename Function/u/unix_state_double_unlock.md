# Function: <code>unix_state_double_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582597191,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:581",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586964704,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1099",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964704,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582840876,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:581",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587411072,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1087",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411072,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582936844,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:581",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587614368,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1092",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614368,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582989589,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:589",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587763904,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1094",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587763904,
      "name": "unix_state_double_unlock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583153915,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:589",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292704,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1095",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292704,
      "name": "unix_state_double_unlock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583359407,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588648736,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1085",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648736,
      "name": "unix_state_double_unlock",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583478162,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588865088,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1092",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865088,
      "name": "unix_state_double_unlock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583662481,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589304816,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1089",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304816,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583768769,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589529200,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529200,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584158878,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590542426,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1124",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584277230,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590602041,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1115",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584302605,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590527257,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1117",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584689037,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591331763,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1203",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585352059,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:615",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593005116,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1283",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586093250,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:635",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594896157,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1336",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586328753,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:635",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595287542,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1357",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586585426,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:635",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596125555,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1341",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495569136,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503204500,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228931880,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 3235872044,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235872044,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289663240,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296929072,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296929072,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274737660,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279235780,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279235780,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583737505,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133568,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589133568,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583674561,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858560,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588858560,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721281,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589570432,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570432,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_unlock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821859,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:590",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589615728,
      "name": "unix_state_double_unlock",
      "external": false,
      "loc": "net/unix/af_unix.c:1101",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589615728,
      "name": "unix_state_double_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void unix_state_double_unlock(struct sock * sk1, struct sock * sk2)
```
</details>
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
