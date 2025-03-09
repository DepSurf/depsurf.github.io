# Function: <code>__lookup_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582511653,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:493",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__lookup_replace",
        "security/apparmor/policy.c:aa_remove_profiles"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582757546,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:518",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:__lookup_replace"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582852717,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:519",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:__lookup_replace"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922800,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:__lookup_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922800,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583082016,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082016,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284656,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:421",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284656,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583403040,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:421",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403040,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589280,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589280,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695440,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695440,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062704,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:420",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062704,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181792,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:420",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181792,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208592,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:420",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208592,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593856,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:420",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593856,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242048,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:463",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242048,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975024,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:520",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975024,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586207120,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:556",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586207120,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586459280,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:583",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459280,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495489128,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495489128,
      "name": "__lookup_profile",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228856656,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228856656,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289551088,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:__lookup_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289551088,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274679552,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:__lookup_replace"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664176,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664176,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601232,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601232,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647952,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647952,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```

```json
{
  "name": "__lookup_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746288,
      "name": "__lookup_profile",
      "external": false,
      "loc": "security/apparmor/policy.c:416",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_remove_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746288,
      "name": "__lookup_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct aa_profile * __lookup_profile(struct aa_policy * base, const char * hname)
```
</details>
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
