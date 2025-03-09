# Function: <code>lsm_cred_alloc</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582643922,
      "name": "lsm_cred_alloc",
      "external": true,
      "loc": "security/security.c:325",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
        "security/security.c:lsm_early_cred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636416,
      "name": "lsm_cred_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582798429,
      "name": "lsm_cred_alloc",
      "external": true,
      "loc": "security/security.c:340",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
        "security/security.c:lsm_early_cred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790256,
      "name": "lsm_cred_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583107333,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:492",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583293605,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:491",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583398725,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583738373,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:578",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank"
      ],
      "caller_func": [
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731760,
      "name": "lsm_cred_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583858702,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:580",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank"
      ],
      "caller_func": [
        "security/security.c:ordered_lsm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852080,
      "name": "lsm_cred_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583884878,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:583",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584248590,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:583",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584858169,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:611",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585562425,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:660",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585793369,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:668",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586041705,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:673",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495151168,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228538780,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289076364,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274398436,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583367461,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583304565,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583351237,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_cred_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583446421,
      "name": "lsm_cred_alloc",
      "external": false,
      "loc": "security/security.c:525",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_prepare_creds",
        "security/security.c:security_cred_alloc_blank",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int lsm_cred_alloc(struct cred * cred, gfp_t gfp)
```
</details>
</li>
</ul>
