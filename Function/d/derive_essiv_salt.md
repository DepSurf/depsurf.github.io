# Function: <code>derive_essiv_salt</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581654867,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:185",
      "file": "fs/crypto/keyinfo.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581799479,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:176",
      "file": "fs/crypto/keyinfo.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581974134,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:221",
      "file": "fs/crypto/keyinfo.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:380",
      "file": "fs/crypto/keyinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059600,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071582062656,
      "name": "derive_essiv_salt.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:379",
      "file": "fs/crypto/keyinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220704,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582223670,
      "name": "derive_essiv_salt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307520,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582310297,
      "name": "derive_essiv_salt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493885344,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493885344,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227366064,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227366064,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287519728,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287519728,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273446324,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273446324,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276256,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582279033,
      "name": "derive_essiv_salt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214016,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582216793,
      "name": "derive_essiv_salt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266736,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582269513,
      "name": "derive_essiv_salt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
```

```json
{
  "name": "derive_essiv_salt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "derive_essiv_salt",
      "external": false,
      "loc": "fs/crypto/keysetup.c:114",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345296,
      "name": "derive_essiv_salt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582348071,
      "name": "derive_essiv_salt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int derive_essiv_salt(const u8 * key, int keysize, u8 * salt)
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
