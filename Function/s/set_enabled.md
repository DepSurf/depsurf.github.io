# Function: <code>set_enabled</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604851235,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:86",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_init",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604851235,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604956258,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:82",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_init",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604956258,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604991821,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604991821,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609272665,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:115",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609272665,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612341542,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:117",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612341542,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614482096,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:118",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614482096,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615428354,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:118",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615428354,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617223465,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:122",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm",
        "security/security.c:prepare_lsm",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617223465,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627932020,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:126",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
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
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619695156,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:127",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
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
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622002052,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:133",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511034980,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511034980,
      "name": "set_enabled.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243515800,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243515800,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302707196,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302707196,
      "name": "set_enabled.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270747754,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270747754,
      "name": "set_enabled.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 106
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604897281,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604897281,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604866333,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604866333,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604974465,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604974465,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
void set_enabled(struct lsm_info * lsm, bool enabled)
```

```json
{
  "name": "set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604995991,
      "name": "set_enabled",
      "external": false,
      "loc": "security/security.c:83",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:ordered_lsm_parse",
        "security/security.c:ordered_lsm_parse",
        "security/security.c:prepare_lsm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604995991,
      "name": "set_enabled",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void set_enabled(struct lsm_info * lsm, bool enabled)
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
