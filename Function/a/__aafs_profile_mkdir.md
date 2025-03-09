# Function: <code>__aafs_profile_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582890784,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1510",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890784,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049232,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1580",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049232,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249792,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1577",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249792,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367808,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1575",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367808,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583554928,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1580",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554928,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660624,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660624,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021264,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1667",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021264,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584141200,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1667",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141200,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584168368,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1667",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168368,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552864,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1667",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552864,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1684",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594086500,
      "name": "__aafs_profile_mkdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585195392,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1865",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100317,
      "name": "__aafs_profile_mkdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585925120,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1913",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596623407,
      "name": "__aafs_profile_mkdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586157312,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1911",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597529716,
      "name": "__aafs_profile_mkdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586406560,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495453712,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495453712,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228820588,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228820588,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289503056,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289503056,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274642848,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274642848,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629360,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629360,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566416,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566416,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613136,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613136,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```

```json
{
  "name": "__aafs_profile_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710992,
      "name": "__aafs_profile_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1548",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710992,
      "name": "__aafs_profile_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __aafs_profile_mkdir(struct aa_profile * profile, struct dentry * parent)
```
</details>
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
