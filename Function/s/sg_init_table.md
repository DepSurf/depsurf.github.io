# Function: <code>sg_init_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014544,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:132",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_page_crypto",
        "fs/ext4/crypto.c:ext4_page_crypto",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/eseqiv.c:eseqiv_givencrypt",
        "crypto/eseqiv.c:eseqiv_givencrypt",
        "lib/scatterlist.c:sg_init_one",
        "lib/scatterlist.c:__sg_alloc_table",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/virtio_blk.c:virtblk_init_request",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014544,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583305873,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:132",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf",
        "lib/scatterlist.c:__sg_alloc_table",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/virtio_blk.c:virtblk_init_request",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305440,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583426145,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:132",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "lib/scatterlist.c:__sg_alloc_table",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424768,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446128,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:132",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446128,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626112,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:132",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626112,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842192,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:126",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_tx_work",
        "kernel/bpf/sockmap.c:bpf_tcp_push",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842192,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925904,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:126",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925904,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105472,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105472,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228368,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228368,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584637488,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634736,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584756496,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753744,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786128,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782208,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585216864,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212864,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586050048,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050048,
      "name": "sg_init_table",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033584,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033584,
      "name": "sg_init_table",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288736,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:126",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/virtio_net.c:virtnet_alloc_queues",
        "drivers/net/virtio_net.c:virtnet_alloc_queues",
        "drivers/net/virtio_net.c:virtnet_commit_rss_command",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:xmit_skb",
        "drivers/net/virtio_net.c:xmit_skb",
        "drivers/net/virtio_net.c:add_recvbuf_big",
        "drivers/net/virtio_net.c:__virtnet_xdp_xmit_one",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288736,
      "name": "sg_init_table",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587574608,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:126",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:__zswap_load",
        "mm/page_reporting.c:page_reporting_process",
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/bsg-lib.c:bsg_map_buffer",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/virtio_net.c:virtnet_alloc_queues",
        "drivers/net/virtio_net.c:virtnet_alloc_queues",
        "drivers/net/virtio_net.c:virtnet_commit_rss_command",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:xmit_skb",
        "drivers/net/virtio_net.c:xmit_skb",
        "drivers/net/virtio_net.c:add_recvbuf_big",
        "drivers/net/virtio_net.c:__virtnet_xdp_xmit_one",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574608,
      "name": "sg_init_table",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496103568,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_rx_dma",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/mmc/core/queue.c:mmc_mq_init_request",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496103568,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229428352,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_rx_dma",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer",
        "drivers/mmc/core/queue.c:mmc_mq_init_request",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229428352,
      "name": "sg_init_table",
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290349952,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "block/bsg-lib.c:bsg_map_buffer",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "lib/sg_pool.c:sg_alloc_table_chained",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290349952,
      "name": "sg_init_table",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275170000,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_init_one"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/mmc/core/queue.c:mmc_mq_init_request",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169922,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197104,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197104,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132320,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132320,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180864,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180864,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void sg_init_table(struct scatterlist * sgl, unsigned int nents)
```

```json
{
  "name": "sg_init_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285200,
      "name": "sg_init_table",
      "external": true,
      "loc": "lib/scatterlist.c:124",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:virt_to_scatterlist",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table",
        "lib/scatterlist.c:sg_init_one",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_rx_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285200,
      "name": "sg_init_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
