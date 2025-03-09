# Function: <code>ima_collect_measurement</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, struct evm_ima_xattr_data * * xattr_value, int * xattr_len)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615696,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:190",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615696,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582862944,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:193",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582862944,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959792,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:193",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959792,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009952,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:194",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009952,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174864,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:194",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174864,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:198",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382371,
      "name": "ima_collect_measurement.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583381040,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:198",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501619,
      "name": "ima_collect_measurement.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583500304,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688472,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583687136,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796168,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583794784,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:209",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188460,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071584186992,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:209",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591370006,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071584305728,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:211",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312694,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071584340064,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:213",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592308639,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071584728816,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:240",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:__ima_inode_hash",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594090947,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585404720,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158400,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:240",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:__ima_inode_hash",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158400,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396352,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:240",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:__ima_inode_hash",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396352,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 881
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661088,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:240",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:__ima_inode_hash",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661088,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495597960,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495597960,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228958720,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228958720,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289702000,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289702000,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274760936,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274760936,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764904,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583763520,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701960,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583700576,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748664,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583747280,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int ima_collect_measurement(struct integrity_iint_cache * iint, struct file * file, void * buf, loff_t size, enum hash_algo algo, struct modsig * modsig)
```

```json
{
  "name": "ima_collect_measurement",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_collect_measurement",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:206",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_appraise.c:ima_update_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849608,
      "name": "ima_collect_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583848224,
      "name": "ima_collect_measurement",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * buf</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t size</code>
</li>
<li>
<b>Param added. </b>
<code>enum hash_algo algo</code>
</li>
<li>
<b>Param removed. </b>
<code>struct evm_ima_xattr_data * * xattr_value</code>
</li>
<li>
<b>Param removed. </b>
<code>int * xattr_len</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct modsig * modsig</code>
</li>
</ul>
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
