# Function: <code>memzero_explicit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982160,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:696",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto_key.c:_ext4_get_encryption_info",
        "fs/ext4/crypto_key.c:_ext4_get_encryption_info",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_entropy",
        "drivers/char/random.c:extract_entropy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982160,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271344,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:693",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271344,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390112,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:693",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed",
        "arch/x86/power/hibernate_64.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390112,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588246240,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:719",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/big_key.c:big_key_crypt",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed",
        "arch/x86/power/hibernate_64.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246240,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797664,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:720",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed",
        "arch/x86/power/hibernate_64.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797664,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175744,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:720",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed",
        "arch/x86/power/hibernate_64.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175744,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589405664,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:721",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405664,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void memzero_explicit(void * s, size_t count)
```

```json
{
  "name": "memzero_explicit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861552,
      "name": "memzero_explicit",
      "external": true,
      "loc": "lib/string.c:763",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/sha1_generic.c:sha1_generic_block_fn",
        "crypto/sha256_generic.c:sha256_transform",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "crypto/ghash-generic.c:ghash_setkey",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861552,
      "name": "memzero_explicit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582300466,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306207,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309027,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126520,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319609,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583340172,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583359859,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376040,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583871863,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583882775,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916022,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583925137,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584289295,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585921052,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581413471,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456887,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kzfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585474,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593210,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593910,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607509,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583651440,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583694609,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:kdf_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715294,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584242632,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584262933,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:crypto_sha1_update",
        "crypto/sha1_generic.c:crypto_sha1_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272838,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308150,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584316305,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616343,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584699403,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586657510,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:248",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_crng_user",
        "drivers/char/random.c:crng_reseed"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581456329,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498364,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656226,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663706,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664558,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582680261,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583772880,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583815969,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:kdf_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836087,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361208,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584381669,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:crypto_sha1_update",
        "crypto/sha1_generic.c:crypto_sha1_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584384785,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391734,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584426790,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584434705,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735159,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584813214,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586515969,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:iterate_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586768054,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_crng_user",
        "drivers/char/random.c:crng_reseed"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581477273,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519244,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685285,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582692874,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582693550,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709013,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583797008,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583840142,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:kdf_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583862951,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395672,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584416165,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:crypto_sha1_update",
        "crypto/sha1_generic.c:crypto_sha1_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419293,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584426099,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461798,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584469377,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584763143,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584857774,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586401022,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586647334,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:242",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_crng_user",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581731737,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782814,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237772,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583010981,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018650,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019326,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035589,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584159552,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584203102,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:kdf_ctr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224615,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584790904,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584811813,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:crypto_sha1_finup",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:crypto_sha1_update",
        "crypto/sha1_generic.c:crypto_sha1_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816569,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584823418,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584857478,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584867505,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191799,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585279217,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha256_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586927710,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194933,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582111567,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170157,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709388,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481491,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489049,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491161,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511549,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584758320,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584829072,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477236,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585501322,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:crypto_sha1_update",
        "crypto/sha1_generic.c:crypto_sha1_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585507561,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514979,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585551722,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585562371,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587853,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/kdf_sp800108.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931923,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120692,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "lib/crypto/blake2s.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/blake2s.c:blake2s_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586130093,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588221816,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496176,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627554082,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585903,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655949,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235100,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076227,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084473,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584086674,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584109197,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585453760,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585529472,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586238340,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264330,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final",
        "crypto/sha1_generic.c:sha1_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586270133,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275283,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586317178,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586325955,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586354297,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "crypto/kdf_sp800108.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586723219,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587110644,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "lib/crypto/blake2s.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/blake2s.c:blake2s_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587120829,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589635416,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936992,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure",
        "drivers/char/random.c:crng_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628159824,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:235",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619303399,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765743,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "arch/x86/crypto/sha512_ssse3_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582793215,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866061,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454857,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584302883,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584312748,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584313442,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585685088,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585761253,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586474212,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586506376,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586511593,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519239,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586561135,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619728372,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/jitterentropy-kcapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/jitterentropy-kcapi.c:jent_mod_init",
        "crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup",
        "crypto/jitterentropy-kcapi.c:jent_read_random_block",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_hash_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586572515,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586600921,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "crypto/kdf_sp800108.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586985623,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587372628,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "lib/crypto/blake2s.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/blake2s.c:blake2s_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587383273,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_transform_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589939084,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590242960,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure",
        "drivers/char/random.c:crng_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619927147,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:236",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621596967,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800687,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "arch/x86/crypto/sha512_ssse3_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582968239,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:kvfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037277,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583646145,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_late",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519907,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530012,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530738,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:put_crypt_info",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931904,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586008677,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586744932,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_tfm_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586775768,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780985,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789191,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831215,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622035972,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/jitterentropy-kcapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/jitterentropy-kcapi.c:jent_mod_init",
        "crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup",
        "crypto/jitterentropy-kcapi.c:jent_read_random_block",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_kvzfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586840787,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870233,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "crypto/kdf_sp800108.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587267367,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587659412,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "lib/crypto/blake2s.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/blake2s.c:blake2s_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670057,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256",
        "lib/crypto/sha256.c:sha224_final",
        "lib/crypto/sha256.c:sha256_transform_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590277963,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590583984,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:mix_interrupt_randomness",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure",
        "drivers/char/random.c:crng_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590619838,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622238283,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:274",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493876144,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493883068,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493886864,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494836340,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495059392,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495084240,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__arm64_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495105232,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495127696,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495690364,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495701312,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495734256,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495743428,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496173748,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498744180,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227358404,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 3227364344,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 3227367604,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228255436,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 3228457480,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228478320,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__se_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228495428,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ],
      "caller_func": []
    },
    {
      "addr": 3228513316,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3229040296,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3229055100,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229087372,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 3229097156,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 3229497176,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 3231360388,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287509848,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287517868,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287522360,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288683112,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288951460,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288983288,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__se_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289009912,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289032856,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289835060,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289849324,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289892264,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289903228,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290440684,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291897012,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273439920,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273444094,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:wipe_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273447788,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274159294,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274329398,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274348334,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__se_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274362988,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274379008,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274838330,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274849534,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274879872,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274892046,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275230718,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276243096,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582269202,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274943,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582277763,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095256,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288345,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583308908,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328595,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344776,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840599,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851511,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583884758,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583893873,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584258031,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585682028,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582206962,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212703,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215523,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032408,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583225481,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583246044,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265699,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281880,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777655,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583788567,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821814,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583830929,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584193231,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585541900,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582259682,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265423,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268243,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083864,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272377,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583292940,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583312371,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328552,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583824359,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583835271,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583868518,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583877633,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241791,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871452,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
  "name": "memzero_explicit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582338274,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/hkdf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582343996,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keyring.c:move_master_key_secret"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582346803,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173112,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583366953,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583387532,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583407395,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423576,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify",
        "security/keys/encrypted-keys/encrypted.c:calc_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583925431,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_generic_block_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936343,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583969590,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583978705,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584346623,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:sha256_transform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585979356,
      "name": "memzero_explicit",
      "external": false,
      "loc": "include/linux/string.h:247",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:crng_reseed"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void memzero_explicit(void * s, size_t count)
```
</details>
</li>
</ul>
