# Function: <code>aa_free_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599232,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:136",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599232,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582842912,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:136",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842912,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582938912,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938912,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582957944,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:141",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957600,
      "name": "aa_free_ns.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071582958176,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583120148,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:141",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119328,
      "name": "aa_free_ns.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071583120368,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583325616,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:141",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325616,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583444176,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:141",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444176,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583629424,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628560,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583629584,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583735600,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734736,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583735760,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119236,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118176,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584119472,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584238192,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237120,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071584238416,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584263088,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263424,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584649040,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649376,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617234920,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:152",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305296,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071585306896,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627947696,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:151",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045168,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071586046016,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619710960,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:151",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280176,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071586281024,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622018048,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:151",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537088,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071586537936,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495532408,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495532008,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446603336495532760,
      "name": "aa_free_ns",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228898628,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228898272,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 3228898880,
      "name": "aa_free_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289614028,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289613392,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 13835058055289614384,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274708608,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274708260,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446743936274708864,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583704336,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703472,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583704496,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641392,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640528,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583641552,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688112,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687248,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583688272,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void aa_free_ns(struct aa_ns * ns)
```

```json
{
  "name": "aa_free_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583787936,
      "name": "aa_free_ns",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:137",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787072,
      "name": "aa_free_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583788096,
      "name": "aa_free_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
