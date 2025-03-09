# Function: <code>initialize_lsm</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604853105,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:207",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:ordered_lsm_init"
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
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604958114,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:203",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:ordered_lsm_init"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604993056,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604993056,
      "name": "initialize_lsm",
      "section": ".init.text",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609273619,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:236",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609273619,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 82
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612342496,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:238",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612342496,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 82
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614483050,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:240",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614483050,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 82
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615429415,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:240",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615429415,
      "name": "initialize_lsm",
      "section": ".init.text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617224612,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:244",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617224612,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 124
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627931328,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:249",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627931328,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619694464,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:250",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619694464,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622001360,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:274",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622001360,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511036052,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511036052,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243517456,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243517456,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 152
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302708520,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302708520,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 168
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270748708,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270748708,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604898516,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604898516,
      "name": "initialize_lsm",
      "section": ".init.text",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604867568,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604867568,
      "name": "initialize_lsm",
      "section": ".init.text",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604975700,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604975700,
      "name": "initialize_lsm",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "initialize_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604997226,
      "name": "initialize_lsm",
      "external": false,
      "loc": "security/security.c:204",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:early_security_init",
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604997226,
      "name": "initialize_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void initialize_lsm(struct lsm_info * lsm)
```
</details>
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
