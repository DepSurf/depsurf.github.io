# Function: <code>crypto_ahash_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582613011,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:470",
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582861689,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:493",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587135462,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:493",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587617110,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:493",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582958537,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:493",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333878,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:493",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587821989,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:493",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583008643,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:499",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587466566,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:499",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587979325,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:499",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583173381,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:503",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271596,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:503",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587988882,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:503",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588515275,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:503",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583379369,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:502",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480306,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:502",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588342598,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:502",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588881975,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:502",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583498513,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:506",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600466,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:506",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588532086,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:506",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105015,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:506",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583685374,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583788029,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942790,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589558059,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582319088,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583792958,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890973,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167222,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589782101,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582608228,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:518",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584182125,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:518",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280573,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:518",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590133862,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:518",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590802558,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:518",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582680980,
      "name": "crypto_ahash_init",
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
      "addr": 18446744071584301357,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584399229,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181622,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590861950,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:526",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582709764,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584338202,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584433517,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590095942,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590793382,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583036404,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726938,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830877,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590870934,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591613158,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583510465,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585402740,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585523468,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592508343,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593305852,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584108033,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586156260,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586284604,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594366231,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595210550,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:528",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586394344,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:559",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528684,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:559",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594754519,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:559",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595601566,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:559",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int crypto_ahash_init(struct ahash_request * req)
```

```json
{
  "name": "crypto_ahash_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_ahash_init",
      "external": true,
      "loc": "crypto/ahash.c:269",
      "file": "crypto/ahash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ao.c:tcp_ao_parse_crypto",
        "net/ipv4/tcp_ao.c:tcp_ao_hash_skb",
        "net/ipv4/tcp_ao.c:tcp_ao_hash_hdr",
        "net/ipv4/tcp_ao.c:tcp_ao_calc_traffic_key",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597532585,
      "name": "crypto_ahash_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586740816,
      "name": "crypto_ahash_init",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493899324,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495596280,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495713404,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502783340,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503491600,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227378856,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3228957224,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 3229065644,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3235485252,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 3236136996,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287536244,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289699776,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289861204,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296423980,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297274160,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273456982,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274759562,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274860830,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278905482,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279461956,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582287824,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583761694,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583859709,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773606,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386469,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582225584,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698750,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583796765,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588485542,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589111461,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582278304,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583745454,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843469,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589209782,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589823333,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
  "name": "crypto_ahash_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582356864,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583846398,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583944541,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250054,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589874389,
      "name": "crypto_ahash_init",
      "external": false,
      "loc": "include/crypto/hash.h:505",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
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
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int crypto_ahash_init(struct ahash_request * req)
```
</details>
</li>
</ul>
