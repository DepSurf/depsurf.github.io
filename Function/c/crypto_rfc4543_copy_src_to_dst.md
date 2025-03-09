# Function: <code>crypto_rfc4543_copy_src_to_dst</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583272873,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1063",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
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
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583478457,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1063",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601968,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1063",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601968,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785456,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1030",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785456,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888368,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888368,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584278032,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:974",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278032,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584396720,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:959",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396720,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584431040,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:959",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431040,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584828400,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:959",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828400,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520496,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:959",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520496,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281248,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:959",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281248,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586525456,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:957",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586525456,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586795488,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:955",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795488,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495707096,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495707096,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229060828,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229060828,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289857040,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289857040,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274855804,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274855804,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857104,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857104,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794160,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794160,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840864,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840864,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
```

```json
{
  "name": "crypto_rfc4543_copy_src_to_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583941936,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "external": false,
      "loc": "crypto/gcm.c:1019",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:crypto_rfc4543_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941936,
      "name": "crypto_rfc4543_copy_src_to_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request * req, bool enc)
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
