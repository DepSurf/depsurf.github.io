# Function: <code>fscrypt_destroy_prepared_key</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582664643,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:145",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665392,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582693635,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:145",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694464,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583019423,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:150",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020304,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583491270,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:151",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy",
        "fs/crypto/keyring.c:fscrypt_key_destroy",
        "fs/crypto/keyring.c:fscrypt_key_destroy",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583492256,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct super_block * sb, struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584086792,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:172",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087936,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct super_block * sb, struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313560,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:172",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314704,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_destroy_prepared_key(struct super_block * sb, struct fscrypt_prepared_key * prep_key)
```

```json
{
  "name": "fscrypt_destroy_prepared_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584530856,
      "name": "fscrypt_destroy_prepared_key",
      "external": true,
      "loc": "fs/crypto/keysetup.c:172",
      "file": "fs/crypto/keysetup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532000,
      "name": "fscrypt_destroy_prepared_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key * prep_key)
```
</details>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block * sb</code>
</li>
<li>
<b>Param reordered. </b>
<code>prep_key</code> ➡️ <code>sb, prep_key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
