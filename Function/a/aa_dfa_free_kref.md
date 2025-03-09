# Function: <code>aa_dfa_free_kref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582486576,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:212",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486576,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582719495,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:216",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719440,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582814151,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:216",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814096,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901728,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:216",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901728,
      "name": "aa_dfa_free_kref",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583059824,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:216",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059824,
      "name": "aa_dfa_free_kref",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260752,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:267",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260752,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583378544,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:267",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378544,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583565344,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:263",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565344,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671072,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671072,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584034251,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:288",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034336,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584153499,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:288",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153584,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584180267,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:288",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180352,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584565291,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:288",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565376,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211063,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:288",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211216,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627945735,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:288",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ],
      "caller_func": [
        "security/apparmor/notify.c:free_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943536,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586175488,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:244",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/notify.c:free_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586175488,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426720,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:244",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:aa_setup_dfa_engine",
        "security/apparmor/notify.c:free_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426720,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495465408,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495465408,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228831972,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228831972,
      "name": "aa_dfa_free_kref",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289518416,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289518416,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274652800,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274652800,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583639808,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639808,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576864,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576864,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583623584,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623584,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_dfa_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_dfa_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721648,
      "name": "aa_dfa_free_kref",
      "external": true,
      "loc": "security/apparmor/match.c:278",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721648,
      "name": "aa_dfa_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
