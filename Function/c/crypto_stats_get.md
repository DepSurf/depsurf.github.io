# Function: <code>crypto_stats_get</code>

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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524624,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1080",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/big_key.c:big_key_crypt",
        "security/keys/big_key.c:big_key_crypt",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/aead.c:aead_init_geniv",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524624,
      "name": "crypto_stats_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712224,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1049",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712224,
      "name": "crypto_stats_get",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583821840,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821840,
      "name": "crypto_stats_get",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219648,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1057",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/geniv.c:aead_init_geniv",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219648,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338032,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1076",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/geniv.c:aead_init_geniv",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338032,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372560,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1076",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/geniv.c:aead_init_geniv",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372560,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584767776,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1058",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/geniv.c:aead_init_geniv",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767776,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452672,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1100",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/geniv.c:aead_init_geniv",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/dh.c:dh_safe_prime_compute_shared_secret",
        "crypto/dh.c:dh_safe_prime_generate_public_key",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452672,
      "name": "crypto_stats_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210496,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1048",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/geniv.c:aead_init_geniv",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/dh.c:dh_safe_prime_compute_shared_secret",
        "crypto/dh.c:dh_safe_prime_generate_public_key",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210496,
      "name": "crypto_stats_get",
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495631464,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495631464,
      "name": "crypto_stats_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228989400,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228989400,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289754576,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289754576,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274787122,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274787122,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790576,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790576,
      "name": "crypto_stats_get",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727632,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727632,
      "name": "crypto_stats_get",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774336,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774336,
      "name": "crypto_stats_get",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875328,
      "name": "crypto_stats_get",
      "external": true,
      "loc": "crypto/algapi.c:1059",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/aead.c:aead_init_geniv",
        "crypto/aead.c:crypto_aead_decrypt",
        "crypto/aead.c:crypto_aead_encrypt",
        "crypto/skcipher.c:crypto_skcipher_decrypt",
        "crypto/skcipher.c:crypto_skcipher_encrypt",
        "crypto/ahash.c:crypto_ahash_digest",
        "crypto/ahash.c:crypto_ahash_finup",
        "crypto/ahash.c:crypto_ahash_final",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:gcm_hash_update",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875328,
      "name": "crypto_stats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void crypto_stats_get(struct crypto_alg * alg)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void crypto_stats_get(struct crypto_alg * alg)
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
