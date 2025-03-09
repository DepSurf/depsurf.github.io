# Function: <code>crypto_stats_ahash_update</code>

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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530704,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1208",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530704,
      "name": "crypto_stats_ahash_update",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718224,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1177",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718224,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828128,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828128,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223232,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1159",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 18446744071584223232,
      "name": "crypto_stats_ahash_update",
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341872,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1178",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 18446744071584341872,
      "name": "crypto_stats_ahash_update",
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376400,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1178",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 18446744071584376400,
      "name": "crypto_stats_ahash_update",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771520,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1160",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 18446744071584771520,
      "name": "crypto_stats_ahash_update",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585455456,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1202",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 18446744071585455456,
      "name": "crypto_stats_ahash_update",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214096,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1150",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 18446744071586214096,
      "name": "crypto_stats_ahash_update",
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495636952,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495636952,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228993956,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
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
      "addr": 3228993956,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289768288,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289768288,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274793624,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274793624,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583796864,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796864,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733920,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733920,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780624,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780624,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_ahash_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881616,
      "name": "crypto_stats_ahash_update",
      "external": true,
      "loc": "crypto/algapi.c:1187",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:gcm_hash_update",
        "lib/iov_iter.c:hash_and_copy_to_iter",
        "net/ipv4/tcp.c:tcp_md5_hash_key",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data",
        "net/ipv4/tcp.c:tcp_md5_hash_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881616,
      "name": "crypto_stats_ahash_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
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
void crypto_stats_ahash_update(unsigned int nbytes, int ret, struct crypto_alg * alg)
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
