# Function: <code>aa_free_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513376,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:200",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_ns.c:aa_free_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513376,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582748992,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:214",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_ns.c:aa_free_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582748992,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844160,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:214",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_ns.c:aa_free_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844160,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582923696,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:210",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923696,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583082944,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:210",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082944,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583285728,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:210",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285728,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583404112,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:210",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404112,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583590352,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590352,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583696512,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696512,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065104,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065104,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183248,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183248,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210048,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210048,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592305869,
      "name": "aa_free_profile.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584595312,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:242",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594087138,
      "name": "aa_free_profile.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585244128,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585980653,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:245",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_learning_profile"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975920,
      "name": "aa_free_profile.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
    },
    {
      "addr": 18446744071585978096,
      "name": "aa_free_profile",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213091,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:282",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_profile"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208864,
      "name": "aa_free_profile.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1011
    },
    {
      "addr": 18446744071586210608,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586465667,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:283",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_profile"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586461024,
      "name": "aa_free_profile.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1035
    },
    {
      "addr": 18446744071586462864,
      "name": "aa_free_profile",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495490128,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495490128,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228857628,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228857628,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289552864,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289552864,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274674182,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274674182,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583665248,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665248,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583602304,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602304,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583649024,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649024,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void aa_free_profile(struct aa_profile * profile)
```

```json
{
  "name": "aa_free_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583747360,
      "name": "aa_free_profile",
      "external": true,
      "loc": "security/apparmor/policy.c:205",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747360,
      "name": "aa_free_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
