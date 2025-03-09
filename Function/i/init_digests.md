# Function: <code>init_digests</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604955734,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604991247,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609272026,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1205",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:init_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609272026,
      "name": "init_digests",
      "section": ".init.text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612340903,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1219",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:init_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612340903,
      "name": "init_digests",
      "section": ".init.text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614481454,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1015",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614481454,
      "name": "init_digests",
      "section": ".init.text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615427712,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1015",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615427712,
      "name": "init_digests",
      "section": ".init.text",
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
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617222794,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1015",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617222794,
      "name": "init_digests",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 117
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
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627929936,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1015",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627929936,
      "name": "init_digests",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 173
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
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619693072,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1015",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619693072,
      "name": "init_digests",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 173
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
int init_digests()
```

```json
{
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621999632,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:1015",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621999632,
      "name": "init_digests",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 173
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511033832,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243515164,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302705864,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270746664,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604896707,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604865759,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604973891,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
  "name": "init_digests",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604995417,
      "name": "init_digests",
      "external": false,
      "loc": "security/keys/trusted.c:1229",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:init_trusted"
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
int init_digests()
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
