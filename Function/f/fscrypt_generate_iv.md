# Function: <code>fscrypt_generate_iv</code>

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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053728,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:136",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053728,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214784,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214784,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295552,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295552,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580128,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:72",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580128,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582651360,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:72",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651360,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582680432,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:72",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680432,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005872,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:72",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005872,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583476112,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:80",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476112,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069952,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:80",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069952,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296032,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:80",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296032,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 index, const struct fscrypt_inode_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512864,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:87",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/inline_crypt.c:fscrypt_generate_dun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512864,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493870544,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493870544,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227352916,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227352916,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287502704,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287502704,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273435414,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273435414,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264288,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264288,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202048,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202048,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254768,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254768,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_generate_iv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333360,
      "name": "fscrypt_generate_iv",
      "external": true,
      "loc": "fs/crypto/crypto.c:138",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333360,
      "name": "fscrypt_generate_iv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void fscrypt_generate_iv(union fscrypt_iv * iv, u64 lblk_num, const struct fscrypt_info * ci)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 index</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 lblk_num</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct fscrypt_info * ci</code> ➡️ <code>const struct fscrypt_inode_info * ci</code>
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
