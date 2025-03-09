# Function: <code>skcipher_alloc_instance_simple</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732320,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1166",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732320,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842000,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842000,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584231328,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:934",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231328,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584349936,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:934",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349936,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384176,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:929",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384176,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584779408,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:929",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779408,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585464656,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:929",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585464656,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586224320,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:929",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586224320,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586460048,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:980",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460048,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586731088,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1103",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731088,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495655384,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495655384,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229009452,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229009452,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289793760,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289793760,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274808424,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274808424,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810736,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810736,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747792,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747792,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794496,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794496,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```

```json
{
  "name": "skcipher_alloc_instance_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895584,
      "name": "skcipher_alloc_instance_simple",
      "external": true,
      "loc": "crypto/skcipher.c:1170",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895584,
      "name": "skcipher_alloc_instance_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct skcipher_instance * skcipher_alloc_instance_simple(struct crypto_template * tmpl, struct rtattr * * tb, struct crypto_alg * * cipher_alg_ret)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct crypto_alg * * cipher_alg_ret</code>
</li>
</ul>
</details>
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
