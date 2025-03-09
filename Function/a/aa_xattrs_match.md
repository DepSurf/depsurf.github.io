# Function: <code>aa_xattrs_match</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265088,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:313",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265088,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583382944,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:313",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382944,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569728,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569728,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675504,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675504,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584042047,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584161860,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584188796,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:311",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584573836,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:311",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585220672,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:298",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585953117,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:305",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586183987,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:305",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586435343,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:find_attach"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495470512,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495470512,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228836804,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228836804,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289525392,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289525392,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274657978,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274657978,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644240,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644240,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583581296,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583581296,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628016,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628016,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```

```json
{
  "name": "aa_xattrs_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726080,
      "name": "aa_xattrs_match",
      "external": false,
      "loc": "security/apparmor/domain.c:309",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:find_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726080,
      "name": "aa_xattrs_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int aa_xattrs_match(const struct linux_binprm * bprm, struct aa_profile * profile, unsigned int state)
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
