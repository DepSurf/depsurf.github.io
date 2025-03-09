# Function: <code>ima_calc_buffer_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582861248,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:626",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861248,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958096,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:628",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958096,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583008224,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:628",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008224,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583172944,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:616",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583172944,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:618",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380042,
      "name": "ima_calc_buffer_hash.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583378896,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1030
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:632",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499283,
      "name": "ima_calc_buffer_hash.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071583498192,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 918
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:626",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583686082,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583685072,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793704,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583792656,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185152,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:775",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185152,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304192,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:765",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304192,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:765",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312617,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584337904,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:765",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592308562,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584726640,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:766",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594090849,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585402368,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586155888,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:766",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586155888,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586393968,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:766",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393968,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586658688,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:766",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658688,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495595960,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495595960,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228956884,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228956884,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289699376,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289699376,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274759304,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274759304,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762440,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583761392,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699496,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583698448,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746200,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583745152,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```

```json
{
  "name": "ima_calc_buffer_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_calc_buffer_hash",
      "external": true,
      "loc": "security/integrity/ima/ima_crypto.c:634",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847144,
      "name": "ima_calc_buffer_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583846096,
      "name": "ima_calc_buffer_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int ima_calc_buffer_hash(const void * buf, loff_t len, struct ima_digest_data * hash)
```
</details>
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
