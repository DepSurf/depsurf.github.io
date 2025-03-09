# Function: <code>security_get_bools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_get_bools(int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582355680,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2585",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355680,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int security_get_bools(int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582576736,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2579",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576736,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int security_get_bools(int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669952,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2579",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669952,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int security_get_bools(int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582762752,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2695",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762752,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int security_get_bools(int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582918768,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2705",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918768,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583114529,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2809",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107808,
      "name": "security_get_bools.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071583119072,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583230319,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2775",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224176,
      "name": "security_get_bools.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071583235088,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583417323,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2788",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410720,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071583421888,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583523227,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516624,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071583527792,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_get_bools(struct selinux_state * state, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583867197,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2838",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_preserve_bools"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_preserve_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866752,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071583877088,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996896,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2937",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_preserve_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996896,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024480,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:3015",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024480,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584394576,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:3022",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394576,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585020544,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:3024",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020544,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738032,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:3017",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738032,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585968752,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2964",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968752,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy * policy, u32 * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586217648,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2973",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217648,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495291492,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495280616,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446603336495296352,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228673036,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228665768,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 3228677412,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289275456,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289266288,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 13835058055289283216,
      "name": "security_get_bools",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274513876,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274507386,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446743936274517428,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583491963,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485360,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071583496528,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583429035,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422432,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071583433584,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583475739,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469136,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071583480304,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int security_get_bools(struct selinux_state * state, int * len, char * * * names, int * * values)
```

```json
{
  "name": "security_get_bools",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583571899,
      "name": "security_get_bools",
      "external": true,
      "loc": "security/selinux/ss/services.c:2795",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565328,
      "name": "security_get_bools.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071583576464,
      "name": "security_get_bools",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<code>len, names, values</code> ➡️ <code>state, len, names, values</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int * len</code> ➡️ <code>u32 * len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy * policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
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
