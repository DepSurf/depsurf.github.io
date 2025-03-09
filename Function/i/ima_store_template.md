# Function: <code>ima_store_template</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615104,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:88",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615104,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582862320,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:88",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582862320,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959168,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:88",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959168,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009312,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:88",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009312,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174224,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:88",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174224,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:89",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382359,
      "name": "ima_store_template.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583380416,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:89",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501607,
      "name": "ima_store_template.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583499680,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688460,
      "name": "ima_store_template.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583686496,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796156,
      "name": "ima_store_template.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583794160,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584186730,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:102",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186448,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584305466,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:102",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305184,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584339802,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:102",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339520,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584728538,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:102",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584728256,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585404441,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:103",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585404128,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586158089,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:103",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157760,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586396028,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:102",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395696,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586660764,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:102",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660432,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495597224,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495597224,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228958096,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228958096,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289701200,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289701200,
      "name": "ima_store_template",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274760430,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274760430,
      "name": "ima_store_template",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764892,
      "name": "ima_store_template.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583762896,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701948,
      "name": "ima_store_template.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583699952,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748652,
      "name": "ima_store_template.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583746656,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int ima_store_template(struct ima_template_entry * entry, int violation, struct inode * inode, const unsigned char * filename, int pcr)
```

```json
{
  "name": "ima_store_template",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_store_template",
      "external": true,
      "loc": "security/integrity/ima/ima_api.c:91",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849596,
      "name": "ima_store_template.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583847600,
      "name": "ima_store_template",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
<code>int pcr</code>
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
