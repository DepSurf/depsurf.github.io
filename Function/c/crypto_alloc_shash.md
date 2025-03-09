# Function: <code>crypto_alloc_shash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582662032,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:576",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662032,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907472,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:429",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907472,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007200,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:429",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007200,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057568,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:430",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057568,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583223712,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:450",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583223712,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583431696,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:450",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583431696,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553136,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:459",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/keyinfo.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553136,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742320,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/keyinfo.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742320,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852112,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852112,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240608,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:505",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/fname.c:fscrypt_do_sha256",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:kdf_alloc",
        "security/keys/trusted-keys/trusted_tpm1.c:init_trusted",
        "security/keys/trusted-keys/trusted_tpm1.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "arch/x86/power/hibernate.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240608,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584359168,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:505",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:kdf_alloc",
        "security/keys/trusted-keys/trusted_tpm1.c:init_trusted",
        "security/keys/trusted-keys/trusted_tpm1.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo",
        "arch/x86/power/hibernate.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584359168,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584393632,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:517",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:kdf_alloc",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393632,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788864,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:517",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:kdf_alloc",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/digsig.c:digsig_init",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788864,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474800,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:517",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/digsig.c:digsig_init",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474800,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586234464,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:507",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/digsig.c:digsig_init",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234464,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586470496,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:572",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_mod_init",
        "crypto/jitterentropy-kcapi.c:jent_kcapi_init",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/digsig.c:digsig_init",
        "drivers/base/firmware_loader/main.c:fw_log_firmware_info",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470496,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586743248,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:302",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_check_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_mod_init",
        "crypto/jitterentropy-kcapi.c:jent_kcapi_init",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/digsig.c:digsig_init",
        "drivers/base/firmware_loader/main.c:fw_log_firmware_info",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743248,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495667576,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495667576,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229020216,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229020216,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289806400,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289806400,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274818464,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274818464,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820848,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820848,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757904,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757904,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583804608,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/libcrc32c.c:libcrc32c_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804608,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_shash * crypto_alloc_shash(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_shash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583905648,
      "name": "crypto_alloc_shash",
      "external": true,
      "loc": "crypto/shash.c:447",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/keysetup.c:derive_essiv_salt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:init_trusted",
        "security/keys/trusted.c:init_trusted",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "security/apparmor/crypto.c:init_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_alloc_tfm",
        "security/integrity/ima/ima_crypto.c:ima_init_crypto",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_init_hash_kernel",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/crc-t10dif.c:crc_t10dif_mod_init",
        "lib/digsig.c:digsig_init",
        "arch/x86/power/hibernate.c:get_e820_md5",
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905648,
      "name": "crypto_alloc_shash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
