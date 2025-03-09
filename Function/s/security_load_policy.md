# Function: <code>security_load_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_load_policy(void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356096,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2013",
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
      "addr": 18446744071582356096,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1466
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
int security_load_policy(void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577152,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2007",
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
      "addr": 18446744071582577152,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1490
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
int security_load_policy(void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582670368,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2007",
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
      "addr": 18446744071582670368,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1490
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
int security_load_policy(void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763152,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2038",
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
      "addr": 18446744071582763152,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1468
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
int security_load_policy(void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582919168,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2044",
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
      "addr": 18446744071582919168,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1470
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2108",
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
      "addr": 18446744071583124736,
      "name": "security_load_policy.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071583113984,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1576
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2064",
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
      "addr": 18446744071583240886,
      "name": "security_load_policy.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583229984,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2077",
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
      "addr": 18446744071583427919,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583416736,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1621
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446744071583533825,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583522640,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1621
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2133",
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
      "addr": 18446744071583883221,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071583872768,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1269
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
int security_load_policy(struct selinux_state * state, void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2248",
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
      "addr": 18446744071591366745,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071583997504,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int security_load_policy(struct selinux_state * state, void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2275",
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
      "addr": 18446744071591309700,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584024832,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int security_load_policy(struct selinux_state * state, void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2282",
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
      "addr": 18446744071592300773,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071584394928,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int security_load_policy(struct selinux_state * state, void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2284",
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
      "addr": 18446744071594082097,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071585020912,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
int security_load_policy(struct selinux_state * state, void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2277",
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
      "addr": 18446744071596097050,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585738416,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 967
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
int security_load_policy(void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2240",
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
      "addr": 18446744071596620235,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585969120,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int security_load_policy(void * data, size_t len, struct selinux_load_state * load_state)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2250",
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
      "addr": 18446744071597525905,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586218016,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495290760,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446603336495290760,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1560
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228672308,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 3228672308,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1508
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289274576,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 13835058055289274576,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1948
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274513236,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446743936274513236,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1348
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446744071583502561,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583491376,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1621
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446744071583439617,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583428448,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1615
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446744071583486337,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583475152,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1621
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
int security_load_policy(struct selinux_state * state, void * data, size_t len)
```

```json
{
  "name": "security_load_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_load_policy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2084",
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
      "addr": 18446744071583582701,
      "name": "security_load_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583571312,
      "name": "security_load_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1619
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
<code>data, len</code> ➡️ <code>state, data, len</code>
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
<code>struct selinux_load_state * load_state</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, data, len, load_state</code> ➡️ <code>data, len, load_state</code>
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
