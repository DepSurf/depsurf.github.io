# Function: <code>crypto_alloc_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633008,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:424",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_calculate_md5",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/crypto_null.c:crypto_get_default_null_skcipher",
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633008,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582882544,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:424",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/drbg.c:drbg_init_sym_kernel",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882544,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979152,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:408",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979152,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583028944,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:408",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028944,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194208,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:409",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194208,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402368,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:418",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/pstore/platform.c:pstore_register",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402368,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522912,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:418",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522912,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710384,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:413",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710384,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820000,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820000,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215040,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:402",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/pstore/platform.c:allocate_buf_for_compression",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215040,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333408,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:402",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:allocate_buf_for_compression",
        "crypto/xts.c:xts_init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333408,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367952,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:402",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:allocate_buf_for_compression",
        "crypto/xts.c:xts_init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367952,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763120,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:402",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:allocate_buf_for_compression",
        "crypto/xts.c:xts_init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763120,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446448,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:457",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446448,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586204416,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:456",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204416,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586442816,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:450",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442816,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586708512,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:450",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586708512,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495626576,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495626576,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228985420,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228985420,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289752176,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289752176,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274784852,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274784852,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788736,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788736,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725792,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725792,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583772496,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772496,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct crypto_tfm * crypto_alloc_base(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873488,
      "name": "crypto_alloc_base",
      "external": true,
      "loc": "crypto/api.c:414",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "fs/crypto/keysetup.c:fscrypt_set_derived_key",
        "crypto/xts.c:init_tfm",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873488,
      "name": "crypto_alloc_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
