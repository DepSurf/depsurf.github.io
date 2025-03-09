# Function: <code>aa_may_manage_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label * label, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518208,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:661",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:profile_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518208,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753936,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:691",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753936,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849104,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:692",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849104,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582926576,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:677",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926576,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086240,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086240,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289328,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:683",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289328,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407696,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:683",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407696,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593648,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593648,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699808,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699808,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068864,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:682",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068864,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187728,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:682",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187728,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214448,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:682",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214448,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:682",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592305994,
      "name": "aa_may_manage_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584599872,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:768",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594087261,
      "name": "aa_may_manage_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585248640,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int aa_may_manage_policy(const struct cred * subj_cred, struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:849",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100448,
      "name": "aa_may_manage_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585982016,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int aa_may_manage_policy(const struct cred * subj_cred, struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:884",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596623717,
      "name": "aa_may_manage_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586214496,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int aa_may_manage_policy(const struct cred * subj_cred, struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:916",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597530015,
      "name": "aa_may_manage_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586467056,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495493280,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495493280,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228860800,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228860800,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289557568,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289557568,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274677058,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274677058,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668544,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668544,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605600,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605600,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583652320,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652320,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int aa_may_manage_policy(struct aa_label * label, struct aa_ns * ns, u32 mask)
```

```json
{
  "name": "aa_may_manage_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750768,
      "name": "aa_may_manage_policy",
      "external": true,
      "loc": "security/apparmor/policy.c:678",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750768,
      "name": "aa_may_manage_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ns * ns</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, mask</code> ➡️ <code>label, ns, mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, ns, mask</code> ➡️ <code>subj_cred, label, ns, mask</code>
</li>
</ul>
</details>
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
