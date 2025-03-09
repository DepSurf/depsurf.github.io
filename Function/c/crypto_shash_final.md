# Function: <code>crypto_shash_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660448,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:134",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_compat_digest",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660448,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906576,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:134",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906576,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006304,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:134",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006304,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056672,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:135",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056672,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583222784,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:143",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222784,
      "name": "crypto_shash_final",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430768,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:143",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430768,
      "name": "crypto_shash_final",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552400,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:157",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552400,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741552,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741552,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851344,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851344,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584242343,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:151",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240272,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360919,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:151",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358784,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395383,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:163",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393248,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584790615,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:163",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788480,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476903,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:163",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474400,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586237959,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:153",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235968,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586473072,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:168",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/hmac.c:hmac_final",
        "crypto/jitterentropy-kcapi.c:jent_read_random_block",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586473072,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744576,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:76",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/ahash.c:shash_ahash_finup",
        "crypto/hmac.c:hmac_final",
        "crypto/jitterentropy-kcapi.c:jent_read_random_block",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744576,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495666376,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495666376,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229019356,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/drbg.c:drbg_kcapi_hash",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229019356,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289805072,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/drbg.c:drbg_kcapi_hash",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289805072,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274817478,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/drbg.c:drbg_kcapi_hash",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274817478,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820080,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820080,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757136,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757136,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803840,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803840,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int crypto_shash_final(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "crypto_shash_final",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904880,
      "name": "crypto_shash_final",
      "external": true,
      "loc": "crypto/shash.c:152",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_final",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904880,
      "name": "crypto_shash_final",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
