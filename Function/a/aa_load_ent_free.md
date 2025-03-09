# Function: <code>aa_load_ent_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525296,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:805",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525296,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763280,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:884",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763280,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582858560,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:884",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858560,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582936986,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:969",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935072,
      "name": "aa_load_ent_free.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071582936064,
      "name": "aa_load_ent_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096192,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:969",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096192,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583300080,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1016",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300080,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583418592,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:984",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418592,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604352,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1006",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604352,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710528,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710528,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082848,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1083",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082848,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202240,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1083",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202240,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228560,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1083",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228560,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614176,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1083",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614176,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585265920,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1300",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585265920,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000160,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1291",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000160,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233632,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1320",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233632,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586486784,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1354",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586486784,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495504048,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495504048,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228871712,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228871712,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289573660,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289566096,
      "name": "aa_load_ent_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 13835058055289572784,
      "name": "aa_load_ent_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274686370,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274686370,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679264,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679264,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616320,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616320,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663040,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663040,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void aa_load_ent_free(struct aa_load_ent * ent)
```

```json
{
  "name": "aa_load_ent_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761680,
      "name": "aa_load_ent_free",
      "external": true,
      "loc": "security/apparmor/policy_unpack.c:1010",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761680,
      "name": "aa_load_ent_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
