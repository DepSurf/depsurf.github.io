# Function: <code>unix_state_double_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582596989,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:566",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586961904,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1084",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961904,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582840688,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:566",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587408224,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1072",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408224,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582936656,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:566",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587611616,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1077",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587611616,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582989367,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:574",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587763808,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1079",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587763808,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583153693,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:574",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292608,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1080",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292608,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583359216,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588644640,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1070",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644640,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583477952,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588860704,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1077",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860704,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583662267,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589301408,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1074",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589301408,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583768555,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589525744,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589525744,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584158667,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590542297,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1109",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590524352,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584277019,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590601913,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1100",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590584240,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584302406,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590527129,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1102",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590509776,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584688838,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591331625,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1188",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315856,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585351866,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:600",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593004574,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1268",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592987344,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586093038,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:620",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594895830,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1321",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594875872,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586328542,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:620",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595287181,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1342",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595268192,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586585215,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:620",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596125035,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1328",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596106064,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495568912,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503200168,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503200168,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228931660,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 3235868128,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235868128,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289663040,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296923456,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296923456,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274737514,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279231362,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279231362,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583737291,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589130112,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130112,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583674347,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855104,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588855104,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721067,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589566976,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589566976,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void unix_state_double_lock(struct sock * sk1, struct sock * sk2)
```

```json
{
  "name": "unix_state_double_lock",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821647,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "security/apparmor/af_unix.c:575",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589615632,
      "name": "unix_state_double_lock",
      "external": false,
      "loc": "net/unix/af_unix.c:1086",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_connect",
        "net/unix/af_unix.c:unix_dgram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589615632,
      "name": "unix_state_double_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
