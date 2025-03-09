# Function: <code>keyctl_pkey_params_parse</code>

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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583070138,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:42",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583254904,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583360760,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int keyctl_pkey_params_parse(struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696576,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696576,
      "name": "keyctl_pkey_params_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int keyctl_pkey_params_parse(struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817872,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817872,
      "name": "keyctl_pkey_params_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583842137,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584205097,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584807644,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585506044,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585737676,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585984924,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495107156,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228497684,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289011116,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274364612,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583329496,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583266600,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583313272,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "keyctl_pkey_params_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583408296,
      "name": "keyctl_pkey_params_parse",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:38",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int keyctl_pkey_params_parse(struct kernel_pkey_params * params)
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
int keyctl_pkey_params_parse(struct kernel_pkey_params * params)
```
</details>
</li>
</ul>
