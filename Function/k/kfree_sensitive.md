# Function: <code>kfree_sensitive</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498320,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1129",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keysetup_v1.c:setup_v1_file_key_derived",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/domain.c:aa_free_domain_entries",
        "security/apparmor/domain.c:aa_free_domain_entries",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/ahash.c:ahash_setkey_unaligned",
        "crypto/shash.c:shash_setkey_unaligned",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/drbg.c:drbg_alloc_state",
        "crypto/drbg.c:drbg_alloc_state",
        "crypto/drbg.c:drbg_alloc_state",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/mpi/mpiutil.c:mpi_snatch",
        "lib/mpi/mpiutil.c:mpi_free",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free",
        "arch/x86/power/hibernate.c:get_e820_md5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498320,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519200,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1226",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_core.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/domain.c:aa_free_domain_entries",
        "security/apparmor/domain.c:aa_free_domain_entries",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/ahash.c:ahash_setkey_unaligned",
        "crypto/shash.c:shash_setkey_unaligned",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/mpi/mpiutil.c:mpi_snatch",
        "lib/mpi/mpiutil.c:mpi_free",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519200,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782784,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1260",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_core.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/domain.c:aa_free_domain_entries",
        "security/apparmor/domain.c:aa_free_domain_entries",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/ahash.c:ahash_setkey_unaligned",
        "crypto/shash.c:shash_setkey_unaligned",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/mpi/mpiutil.c:mpi_snatch",
        "lib/mpi/mpiutil.c:mpi_free",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782784,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170128,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1237",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_core.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/ahash.c:ahash_setkey_unaligned",
        "crypto/shash.c:shash_setkey_unaligned",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/mpi/mpiutil.c:mpi_snatch",
        "lib/mpi/mpiutil.c:mpi_free",
        "lib/mpi/mpiutil.c:mpi_resize",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170128,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655920,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1417",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keyring.c:fscrypt_free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_core.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/ahash.c:ahash_setkey_unaligned",
        "crypto/shash.c:shash_setkey_unaligned",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "lib/crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "lib/mpi/mpiutil.c:mpi_snatch",
        "lib/mpi/mpiutil.c:mpi_free",
        "lib/mpi/mpiutil.c:mpi_resize",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655920,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582866032,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1425",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keyring.c:fscrypt_free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_core.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/notify.c:aa_free_ruleset",
        "security/apparmor/notify.c:aa_free_ruleset",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/ahash.c:ahash_save_req",
        "crypto/ahash.c:ahash_setkey_unaligned",
        "crypto/shash.c:shash_setkey_unaligned",
        "crypto/akcipher.c:crypto_akcipher_sync_post",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/jitterentropy-testing.c:jent_raw_hires_read",
        "crypto/jitterentropy-testing.c:jent_raw_hires_read",
        "crypto/jitterentropy-testing.c:jent_raw_hires_read",
        "crypto/jitterentropy-testing.c:jent_raw_hires_read",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "lib/crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "lib/mpi/mpiutil.c:mpi_snatch",
        "lib/mpi/mpiutil.c:mpi_free",
        "lib/mpi/mpiutil.c:mpi_resize",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866032,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void kfree_sensitive(const void * p)
```

```json
{
  "name": "kfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583037248,
      "name": "kfree_sensitive",
      "external": true,
      "loc": "mm/slab_common.c:1239",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_destroy",
        "fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring",
        "fs/crypto/keyring.c:fscrypt_free_master_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_get_direct_key",
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key",
        "fs/crypto/keysetup_v1.c:fscrypt_put_direct_key",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon",
        "security/keys/user_defined.c:user_destroy",
        "security/keys/user_defined.c:user_free_payload_rcu",
        "security/keys/user_defined.c:user_free_preparse",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted-keys/trusted_core.c:trusted_destroy",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_rcu_free",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/keys/encrypted-keys/encrypted.c:encrypted_destroy",
        "security/keys/encrypted-keys/encrypted.c:encrypted_read",
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:get_derived_key",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/lib.c:aa_free_str_table",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy.c:aa_free_data",
        "security/apparmor/policy_unpack.c:aa_load_ent_free",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_unpack.c:do_loaddata_free",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/notify.c:aa_free_ruleset",
        "security/apparmor/notify.c:aa_free_ruleset",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:free_listener",
        "security/apparmor/notify.c:aa_free_listener_proxy",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/lskcipher.c:crypto_lskcipher_crypt_unaligned",
        "crypto/lskcipher.c:crypto_lskcipher_crypt_unaligned",
        "crypto/lskcipher.c:lskcipher_setkey_unaligned",
        "crypto/skcipher.c:skcipher_setkey_unaligned",
        "crypto/seqiv.c:seqiv_aead_encrypt_complete2",
        "crypto/ahash.c:ahash_restore_req",
        "crypto/akcipher.c:crypto_akcipher_sync_post",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/dh.c:dh_safe_prime_set_secret",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "crypto/acompress.c:acomp_request_free",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/deflate.c:deflate_free_ctx",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_fini_sym_kernel",
        "crypto/drbg.c:drbg_fini_hash_kernel",
        "crypto/jitterentropy-kcapi.c:jent_zfree",
        "crypto/ghash-generic.c:ghash_exit_tfm",
        "crypto/ghash-generic.c:ghash_setkey",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "lib/crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "lib/crypto/mpi/mpiutil.c:mpi_snatch",
        "lib/crypto/mpi/mpiutil.c:mpi_free",
        "lib/crypto/mpi/mpiutil.c:mpi_resize",
        "net/core/sock.c:sock_kzfree_s",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free",
        "net/ipv4/tcp_sigpool.c:tcp_sigpool_end",
        "net/ipv4/tcp_ao.c:tcp_ao_add_cmd",
        "net/ipv4/tcp_ao.c:tcp_ao_parse_crypto",
        "net/ipv4/tcp_ao.c:tcp_ao_parse_crypto",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching",
        "net/ipv4/tcp_ao.c:tcp_ao_key_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037248,
      "name": "kfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void kfree_sensitive(const void * p)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
