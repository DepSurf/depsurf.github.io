# Function: <code>ima_get_modsig_digest</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810944,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810944,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205440,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205440,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584323760,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:122",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323760,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358320,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:122",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358320,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584751376,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:122",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751376,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432336,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:122",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432336,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586188352,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:122",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188352,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426080,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:125",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426080,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691152,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:125",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691152,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495616080,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495616080,
      "name": "ima_get_modsig_digest",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228975704,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228975704,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289733408,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289733408,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274776162,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274776162,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779680,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779680,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583716736,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716736,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583763440,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763440,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```

```json
{
  "name": "ima_get_modsig_digest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864432,
      "name": "ima_get_modsig_digest",
      "external": true,
      "loc": "security/integrity/ima/ima_modsig.c:142",
      "file": "security/integrity/ima/ima_modsig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init",
        "security/integrity/ima/ima_appraise.c:ima_check_blacklist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864432,
      "name": "ima_get_modsig_digest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int ima_get_modsig_digest(const struct modsig * modsig, enum hash_algo * algo, const u8 * * digest, u32 * digest_size)
```
</details>
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
