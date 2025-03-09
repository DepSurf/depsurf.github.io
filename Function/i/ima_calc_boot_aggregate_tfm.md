# Function: <code>ima_calc_boot_aggregate_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595204690,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:534",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
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
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595380187,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:652",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
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
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595628581,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:654",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
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
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596560579,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:654",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
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
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602887889,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:642",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
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
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603061017,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:644",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604863150,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:658",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604863150,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604969016,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:652",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604969016,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605005007,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605005007,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:809",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181536,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071584185643,
      "name": "ima_calc_boot_aggregate_tfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:799",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300768,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071591369775,
      "name": "ima_calc_boot_aggregate_tfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:799",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335120,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071591312478,
      "name": "ima_calc_boot_aggregate_tfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:799",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584723440,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071592308423,
      "name": "ima_calc_boot_aggregate_tfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:800",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398928,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071594090735,
      "name": "ima_calc_boot_aggregate_tfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152176,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:800",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152176,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586390368,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:800",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390368,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int ima_calc_boot_aggregate_tfm(char * digest, u16 alg_id, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654720,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:800",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654720,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511049504,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511049504,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 292
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243531308,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243531308,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 276
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302725508,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302725508,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 344
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270759646,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270759646,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604910467,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604910467,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604879519,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604879519,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604987639,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604987639,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_boot_aggregate_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605009177,
      "name": "ima_calc_boot_aggregate_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:660",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605009177,
      "name": "ima_calc_boot_aggregate_tfm",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
int ima_calc_boot_aggregate_tfm(char * digest, struct crypto_shash * tfm)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 alg_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>digest, tfm</code> ➡️ <code>digest, alg_id, tfm</code>
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
