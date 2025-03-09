# Function: <code>crypto_shash_digest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660816,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:175",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "crypto/shash.c:shash_compat_digest",
        "crypto/hmac.c:hmac_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660816,
      "name": "crypto_shash_digest",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906960,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:175",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "crypto/hmac.c:hmac_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906960,
      "name": "crypto_shash_digest",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006688,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:175",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "crypto/hmac.c:hmac_setkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006688,
      "name": "crypto_shash_digest",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057056,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:176",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057056,
      "name": "crypto_shash_digest",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583223184,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:184",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583223184,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583431168,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:184",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583431168,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552640,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:198",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:key_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552640,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741824,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741824,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851616,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851616,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242432,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:192",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "arch/x86/power/hibernate.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242432,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361008,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:192",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "arch/x86/power/hibernate.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361008,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395472,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:204",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395472,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584790704,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:204",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790704,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585477008,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:204",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585477008,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586238096,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:194",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586238096,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586473968,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:227",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/verity/hash_algs.c:fsverity_hash_block",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "drivers/base/firmware_loader/main.c:fw_log_firmware_info",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586473968,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744736,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:128",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash",
        "fs/verity/hash_algs.c:fsverity_hash_block",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "crypto/ahash.c:shash_ahash_digest",
        "crypto/shash.c:crypto_shash_tfm_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "drivers/base/firmware_loader/main.c:fw_log_firmware_info",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744736,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495666864,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495666864,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229019640,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229019640,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289805616,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289805616,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274817878,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274817878,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820352,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820352,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757408,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757408,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583804112,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804112,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int crypto_shash_digest(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out)
```

```json
{
  "name": "crypto_shash_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583905152,
      "name": "crypto_shash_digest",
      "external": true,
      "loc": "crypto/shash.c:193",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:hkdf_extract",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ecryptfs/crypto.c:ecryptfs_hash_digest",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/encrypted-keys/encrypted.c:calc_hash",
        "crypto/shash.c:shash_ahash_digest",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905152,
      "name": "crypto_shash_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
