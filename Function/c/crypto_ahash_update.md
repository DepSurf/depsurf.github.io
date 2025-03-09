# Function: <code>crypto_ahash_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582613471,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:487",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582861838,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587049398,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587135337,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616212,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582958686,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244870,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333753,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587821076,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:510",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583008833,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:516",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375398,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:516",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587466442,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:516",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587978315,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:516",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583173489,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:524",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271467,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:524",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587895862,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:524",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587988746,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:524",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588514283,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:524",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583379462,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:523",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480187,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:523",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588242774,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:523",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588342468,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:523",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588880616,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:523",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583498614,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:527",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583598619,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:527",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945690,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:527",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588440598,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:527",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588531910,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:527",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589103964,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:527",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583685461,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583787069,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584127759,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837544,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942613,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589556959,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582319131,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583793045,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890013,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584247633,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589060728,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167045,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589780991,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582608344,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584182217,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584279597,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584660193,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590024195,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590133675,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590802362,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:539",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582681096,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584301449,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584398253,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584770737,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590065955,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181435,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590861754,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:547",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582709880,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584338296,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432560,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815217,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589980307,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590095755,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590790634,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583036520,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584727032,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829920,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585239841,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590749011,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590870747,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591608202,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583510615,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585402838,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585522324,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586078733,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592382034,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592508153,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593301525,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584108183,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586156358,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586282548,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587054125,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594230722,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594366025,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595205557,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:549",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586394437,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:601",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586525343,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:601",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587306535,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:601",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594618482,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:601",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594754325,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:601",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595601361,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:601",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int crypto_ahash_update(struct ahash_request * req)
```

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_ahash_update",
      "external": true,
      "loc": "crypto/ahash.c:344",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue",
        "net/core/datagram.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers",
        "net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data",
        "net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data",
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
      "addr": 18446744071597532627,
      "name": "crypto_ahash_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586741968,
      "name": "crypto_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493899384,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495596360,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495711276,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496125624,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502672512,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502783148,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503485960,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227378908,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3228957320,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 3229064540,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3229448720,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3235376608,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3235485068,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 3236136120,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_headers"
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287536304,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289699884,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289859664,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290378008,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296281652,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296423724,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297272936,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273457042,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274759636,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274859312,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275185656,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278810430,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278905336,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279461026,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582287867,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583761781,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858749,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216369,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588667112,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773429,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589385359,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582225627,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698837,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583795805,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151585,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588379096,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588485365,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589110351,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582278347,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583745541,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842509,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584200129,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589103288,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589209605,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589822223,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_ahash_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582356907,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583846485,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583943581,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584304641,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:hash_and_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589143048,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249877,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589873279,
      "name": "crypto_ahash_update",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int crypto_ahash_update(struct ahash_request * req)
```
</details>
</li>
</ul>
