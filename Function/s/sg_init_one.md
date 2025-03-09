# Function: <code>sg_init_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014608,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:153",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto_key.c:ext4_derive_key_aes",
        "fs/ext4/crypto_key.c:ext4_derive_key_aes",
        "fs/ext4/crypto_fname.c:ext4_fname_encrypt",
        "fs/ext4/crypto_fname.c:ext4_fname_encrypt",
        "fs/ext4/crypto_fname.c:ext4_fname_decrypt",
        "fs/ext4/crypto_fname.c:ext4_fname_decrypt",
        "fs/ecryptfs/crypto.c:ecryptfs_calculate_md5",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:__send_control_msg",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_header",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_pseudoheader",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_pseudoheader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014608,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305856,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:153",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/big_key.c:big_key_crypt",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/block/virtio_blk.c:__virtblk_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_header",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305856,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426128,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:153",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/big_key.c:big_key_crypt",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "arch/x86/power/hibernate_64.c:get_e820_md5",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426128,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448592,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:153",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/big_key.c:big_key_crypt",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "arch/x86/power/hibernate_64.c:get_e820_md5",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448592,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627264,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:153",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/keys/big_key.c:big_key_crypt",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_crypt_remain_continue",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "arch/x86/power/hibernate_64.c:get_e820_md5",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627264,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843552,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:140",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "arch/x86/power/hibernate_64.c:get_e820_md5",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843552,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927248,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:140",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927248,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107136,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107136,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584231680,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231680,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584637488,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_len",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637488,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756496,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_len",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756496,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786128,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_crypt_remain_continue",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786128,
      "name": "sg_init_one",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585216864,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_crypt_remain_continue",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585216864,
      "name": "sg_init_one",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586050128,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_crypt_remain_continue",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050128,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033680,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_crypt_remain_continue",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033680,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288832,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:140",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/akcipher.c:crypto_akcipher_sync_prep",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_len",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/block/virtio_blk.c:virtblk_add_req",
        "drivers/block/virtio_blk.c:virtblk_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-scsi.c:atapi_request_sense",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_set_coalesce",
        "drivers/net/virtio_net.c:virtnet_set_coalesce",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288832,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587574704,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:140",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:__zswap_load",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/akcipher.c:crypto_akcipher_sync_prep",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:gcm_hash_len",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "drivers/virtio/virtio_pci_modern.c:vp_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_set_status",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec",
        "drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_notify_info",
        "drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_read",
        "drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_read",
        "drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_write",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/block/virtio_blk.c:virtblk_add_req",
        "drivers/block/virtio_blk.c:virtblk_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_set_coalesce",
        "drivers/net/virtio_net.c:virtnet_send_rx_notf_coal_cmds",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/core/datagram.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv4/tcp_ao.c:tcp_ao_parse_crypto",
        "net/ipv4/tcp_ao.c:tcp_ao_hash_skb",
        "net/ipv4/tcp_ao.c:tcp_ao_hash_skb",
        "net/ipv4/tcp_ao.c:tcp_ao_hash_hdr",
        "net/ipv4/tcp_ao.c:tcp_ao_hash_hdr",
        "net/ipv4/tcp_ao.c:tcp_ao_calc_traffic_key",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_hash_pseudoheader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574704,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496105320,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/iommu/virtio-iommu.c:__viommu_add_req",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496105320,
      "name": "sg_init_one",
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229432324,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229432324,
      "name": "sg_init_one",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290352352,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290352352,
      "name": "sg_init_one",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275170000,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275170000,
      "name": "sg_init_one",
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200416,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200416,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584135632,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135632,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184176,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:__virtscsi_add_cmd",
        "drivers/scsi/virtio_scsi.c:virtscsi_kick_event",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184176,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void sg_init_one(struct scatterlist * sg, const void * buf, unsigned int buflen)
```

```json
{
  "name": "sg_init_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288528,
      "name": "sg_init_one",
      "external": true,
      "loc": "lib/scatterlist.c:138",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_module_init",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:put_chars",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/scsi_error.c:scsi_eh_prep_cmnd",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/ipv4/tcp.c:tcp_md5_hash_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288528,
      "name": "sg_init_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
