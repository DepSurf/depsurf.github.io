# Function: <code>security_cred_getsecid</code>

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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985584,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1026",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985584,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097360,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1618",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097360,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280576,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1637",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280576,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386544,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386544,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728976,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1844",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728976,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849184,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1846",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849184,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874384,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1896",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874384,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584238800,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1904",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584238800,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584844896,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1909",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584844896,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585547024,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1956",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547024,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void security_cred_getsecid(const struct cred * c, struct lsmblob * blob)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777488,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:3114",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777488,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586020912,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:3181",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020912,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495136224,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495136224,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228524192,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228524192,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289049632,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289049632,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274387182,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274387182,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355280,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355280,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292384,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292384,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339056,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339056,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
```

```json
{
  "name": "security_cred_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583434240,
      "name": "security_cred_getsecid",
      "external": true,
      "loc": "security/security.c:1676",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_bprm_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583434240,
      "name": "security_cred_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_cred_getsecid(const struct cred * c, u32 * secid)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * secid</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * secid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lsmblob * blob</code>
</li>
</ul>
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
