# Function: <code>fscrypt_msg</code>

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
void fscrypt_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968420,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:426",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyinfo.c:find_and_lock_process_key",
        "fs/crypto/keyinfo.c:find_and_lock_process_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968420,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void fscrypt_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055332,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:428",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyinfo.c:derive_essiv_salt",
        "fs/crypto/keyinfo.c:find_and_lock_process_key",
        "fs/crypto/keyinfo.c:find_and_lock_process_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055332,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void fscrypt_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216364,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:456",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyinfo.c:derive_essiv_salt",
        "fs/crypto/keyinfo.c:find_and_lock_process_key",
        "fs/crypto/keyinfo.c:find_and_lock_process_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216364,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297204,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297204,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581732,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:332",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/fname.c:fscrypt_do_sha256",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:check_for_busy_inodes",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581732,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591341180,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:332",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:check_for_busy_inodes",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341180,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591283913,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:332",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591283913,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592239281,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:332",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592239281,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594017522,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:340",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594017522,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070384,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:340",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_encryption_info",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070384,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296480,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:347",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296480,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513312,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:365",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_file_encryption_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513312,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493872592,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493872592,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227355052,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227355052,
      "name": "fscrypt_msg",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287505236,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287505236,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273437020,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273437020,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265940,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265940,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203700,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203700,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256420,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256420,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fscrypt_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fscrypt_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582335012,
      "name": "fscrypt_msg",
      "external": true,
      "loc": "fs/crypto/crypto.c:454",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/keysetup_v1.c:find_and_lock_process_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/crypto/policy.c:fscrypt_supported_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335012,
      "name": "fscrypt_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fscrypt_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct super_block * sb</code>
</li>
</ul>
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
