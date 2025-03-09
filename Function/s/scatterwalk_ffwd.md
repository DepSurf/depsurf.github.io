# Function: <code>scatterwalk_ffwd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640832,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:150",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640832,
      "name": "scatterwalk_ffwd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582890112,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:81",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890112,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582986688,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:77",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986688,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583036640,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:77",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036640,
      "name": "scatterwalk_ffwd",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583201952,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:77",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201952,
      "name": "scatterwalk_ffwd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583410432,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:77",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410432,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583532144,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:77",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532144,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583720096,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720096,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583829808,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829808,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225248,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225248,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584343632,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584343632,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378112,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378112,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773344,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773344,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585457632,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457632,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216496,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216496,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586451872,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451872,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717760,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scatterwalk.c:scatterwalk_map_and_copy",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717760,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495640336,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495640336,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228996148,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228996148,
      "name": "scatterwalk_ffwd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289771376,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289771376,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274795630,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274795630,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583798544,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798544,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583735600,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735600,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583782304,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782304,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * scatterwalk_ffwd(struct scatterlist * dst, struct scatterlist * src, unsigned int len)
```

```json
{
  "name": "scatterwalk_ffwd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583883328,
      "name": "scatterwalk_ffwd",
      "external": true,
      "loc": "crypto/scatterwalk.c:72",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_init_common",
        "crypto/gcm.c:crypto_gcm_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883328,
      "name": "scatterwalk_ffwd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
