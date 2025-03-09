# Function: <code>crypto_shash_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660192,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:98",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_superblock_csum",
        "fs/jbd2/journal.c:journal_get_superblock",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_compat_update",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660192,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906304,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:98",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906304,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006032,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:98",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006032,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056384,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:99",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056384,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583222480,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:107",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222480,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430448,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:107",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430448,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552160,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:115",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552160,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741328,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741328,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851104,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851104,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584242255,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:109",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/recovery.c:scan_revoke_records",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/crc-t10dif.c:crc_t10dif",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240032,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360831,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:109",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/crc-t10dif.c:crc_t10dif_update",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358544,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395295,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:121",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/crc-t10dif.c:crc_t10dif_update",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393008,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584790527,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:121",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/dh.c:kdf_ctr",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/crc-t10dif.c:crc_t10dif_update",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788240,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476804,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:121",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_memcpy",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/crc-t10dif.c:crc_t10dif_update",
        "lib/crc64-rocksoft.c:crc64_rocksoft_update",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474080,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586237860,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:111",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/crc-t10dif.c:crc_t10dif_update",
        "lib/crc64-rocksoft.c:crc64_rocksoft_update",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235616,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586473232,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:120",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/jitterentropy-kcapi.c:jent_read_random_block",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/crc-t10dif.c:crc_t10dif",
        "lib/crc64-rocksoft.c:crc64_rocksoft",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586473232,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744656,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:61",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/super.c:ext4_get_journal_blkdev",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:journal_load_superblock",
        "fs/jbd2/journal.c:journal_check_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/ahash.c:shash_ahash_finup",
        "crypto/ahash.c:shash_ahash_update",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/jitterentropy-kcapi.c:jent_read_random_block",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/jitterentropy-kcapi.c:jent_hash_time",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate",
        "lib/crc-t10dif.c:crc_t10dif",
        "lib/crc64-rocksoft.c:crc64_rocksoft",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744656,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495666032,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495666032,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229019080,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/extents.c:ext4_chksum",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/drbg.c:drbg_kcapi_hash",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229019080,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289804672,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/drbg.c:drbg_kcapi_hash",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289804672,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274817242,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:__ext4_ext_check",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_superblock_csum",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/drbg.c:drbg_kcapi_hash",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274817242,
      "name": "crypto_shash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819840,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819840,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756896,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756896,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803600,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803600,
      "name": "crypto_shash_update",
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
int crypto_shash_update(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "crypto_shash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904640,
      "name": "crypto_shash_update",
      "external": true,
      "loc": "crypto/shash.c:110",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/crypto/hkdf.c:fscrypt_hkdf_expand",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/extents.c:ext4_extent_block_csum",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_profile_hash",
        "security/apparmor/crypto.c:aa_calc_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm",
        "security/integrity/evm/evm_crypto.c:evm_init_hmac",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "crypto/shash.c:shash_ahash_update",
        "crypto/shash.c:shash_finup_unaligned",
        "crypto/hmac.c:hmac_update",
        "crypto/hmac.c:hmac_setkey",
        "crypto/hmac.c:hmac_setkey",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904640,
      "name": "crypto_shash_update",
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
