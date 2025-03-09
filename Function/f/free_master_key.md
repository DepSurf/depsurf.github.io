# Function: <code>free_master_key</code>

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
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582060671,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:282",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:put_crypt_info",
        "fs/crypto/keyinfo.c:find_or_insert_master_key"
      ],
      "caller_func": [
        "fs/crypto/keyinfo.c:put_crypt_info",
        "fs/crypto/keyinfo.c:find_or_insert_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059840,
      "name": "free_master_key.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582221309,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:281",
      "file": "fs/crypto/keyinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:put_crypt_info",
        "fs/crypto/keyinfo.c:find_or_insert_master_key"
      ],
      "caller_func": [
        "fs/crypto/keyinfo.c:put_crypt_info",
        "fs/crypto/keyinfo.c:find_or_insert_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220928,
      "name": "free_master_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303168,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303168,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588704,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:41",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588704,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659264,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:41",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659264,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582688512,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:41",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688512,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014224,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:41",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014224,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583486506,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:41",
      "file": "fs/crypto/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493879144,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493879144,
      "name": "free_master_key",
      "section": ".text",
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227361152,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227361152,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287513984,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287513984,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273441970,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273441970,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271904,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271904,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209664,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209664,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262384,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262384,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_master_key(struct fscrypt_master_key * mk)
```

```json
{
  "name": "free_master_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340976,
      "name": "free_master_key",
      "external": false,
      "loc": "fs/crypto/keyring.c:40",
      "file": "fs/crypto/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340976,
      "name": "free_master_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_master_key(struct fscrypt_master_key * mk)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void free_master_key(struct fscrypt_master_key * mk)
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
