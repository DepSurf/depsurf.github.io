# Function: <code>add_new_master_key</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582304141,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
```

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588896,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:325",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588896,
      "name": "add_new_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
```

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659456,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:334",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659456,
      "name": "add_new_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
```

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582688704,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:334",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688704,
      "name": "add_new_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
```

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014480,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:334",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014480,
      "name": "add_new_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
```

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583485952,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:334",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485952,
      "name": "add_new_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081856,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:414",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081856,
      "name": "add_new_master_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584308368,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:417",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308368,
      "name": "add_new_master_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584525408,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:424",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525408,
      "name": "add_new_master_key.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493880780,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227361924,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287515164,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273443164,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582272877,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582210637,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582263357,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
  "name": "add_new_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582341949,
      "name": "add_new_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:321",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_master_key"
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
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int add_new_master_key(struct fscrypt_master_key_secret * secret, const struct fscrypt_key_specifier * mk_spec, struct key * keyring)
```
</details>
</li>
</ul>
