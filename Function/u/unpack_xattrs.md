# Function: <code>unpack_xattrs</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583296779,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:548",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583415332,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:516",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583601516,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583707670,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584077200,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:559",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077200,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584196592,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:559",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196592,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223472,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:559",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223472,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608912,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:559",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608912,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258432,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:566",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258432,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585991328,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:534",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585991328,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586224080,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:545",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586224080,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586476784,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:548",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586476784,
      "name": "unpack_xattrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495501180,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228869168,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289569372,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274683862,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583676406,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583613462,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583660182,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unpack_xattrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583758822,
      "name": "unpack_xattrs",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:538",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_profile"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool unpack_xattrs(struct aa_ext * e, struct aa_profile * profile)
```
</details>
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
