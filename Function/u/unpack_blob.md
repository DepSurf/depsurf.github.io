# Function: <code>unpack_blob</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582522502,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:264",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582760853,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:274",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582856350,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:274",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582934427,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:330",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583094653,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:330",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583297239,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:347",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583415789,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:347",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa",
        "security/apparmor/policy_unpack.c:unpack_dfa"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598400,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598400,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704560,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704560,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584076245,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:384",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074304,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584195637,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:384",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193680,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584222517,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:384",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220576,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584607957,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:384",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606016,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585255328,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:383",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585255328,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495497728,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495497728,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228865292,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228865292,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289564240,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289564240,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274680954,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274680954,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673296,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673296,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610352,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610352,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657072,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657072,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```

```json
{
  "name": "unpack_blob",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755584,
      "name": "unpack_blob",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:363",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_dfa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755584,
      "name": "unpack_blob",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
size_t unpack_blob(struct aa_ext * e, char * * blob, const char * name)
```
</details>
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
