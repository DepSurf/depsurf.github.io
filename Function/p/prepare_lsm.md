# Function: <code>prepare_lsm</code>

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
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604852372,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:188",
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
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604957382,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:184",
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604992753,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446744071604992753,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 303
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609273701,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:217",
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
      "addr": 18446744071609273701,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 299
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612342578,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:219",
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
      "addr": 18446744071612342578,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 299
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614483132,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:221",
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
      "addr": 18446744071614483132,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 315
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615429527,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:221",
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
      "addr": 18446744071615429527,
      "name": "prepare_lsm",
      "section": ".init.text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617224736,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:225",
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
      "addr": 18446744071617224736,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 390
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627932784,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:230",
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
      "addr": 18446744071627932784,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 396
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619695968,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:231",
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
      "addr": 18446744071619695968,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 396
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622002864,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:255",
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
      "addr": 18446744071622002864,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 396
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511035728,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446603336511035728,
      "name": "prepare_lsm",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243517096,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 3243517096,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 360
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302708100,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 13835058055302708100,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 420
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270748386,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446743936270748386,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 322
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604898213,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446744071604898213,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 303
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604867265,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446744071604867265,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 303
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604975397,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446744071604975397,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 303
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
void prepare_lsm(struct lsm_info * lsm)
```

```json
{
  "name": "prepare_lsm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604996923,
      "name": "prepare_lsm",
      "external": false,
      "loc": "security/security.c:185",
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
      "addr": 18446744071604996923,
      "name": "prepare_lsm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 303
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
void prepare_lsm(struct lsm_info * lsm)
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
