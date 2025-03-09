# Function: <code>datablob_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215552,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:856",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071582222624,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:177",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215552,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071582222624,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434048,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:856",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071582441264,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:177",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434048,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071582441264,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526240,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:856",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071582533456,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:177",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526240,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071582533456,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609856,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:856",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071582616944,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609856,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071582616944,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763424,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:856",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071582770560,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763424,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071582770560,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582963648,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:855",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963648,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071582971024,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446744071582976602,
      "name": "datablob_parse.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076384,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:859",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:174",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076384,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071583082208,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446744071583087930,
      "name": "datablob_parse.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259520,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259520,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071583267056,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071583272557,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365408,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365408,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071583372832,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071583378623,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699136,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:850",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699136,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071583712656,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071583717005,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820416,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:860",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820416,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071583833488,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071591362336,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * * datablob, struct trusted_key_payload * p)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843648,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_core.c:65",
      "file": "security/keys/trusted-keys/trusted_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843648,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071583859200,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071591305042,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * * datablob, struct trusted_key_payload * p)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206624,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_core.c:65",
      "file": "security/keys/trusted-keys/trusted_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206624,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071584222448,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071592292803,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * * datablob, struct trusted_key_payload * p)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584809456,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_core.c:74",
      "file": "security/keys/trusted-keys/trusted_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:176",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809456,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071584826528,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071594075070,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * * datablob, struct trusted_key_payload * p)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585508016,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_core.c:74",
      "file": "security/keys/trusted-keys/trusted_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071585527248,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:176",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508016,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071585527248,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * * datablob, struct trusted_key_payload * p)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585739696,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_core.c:74",
      "file": "security/keys/trusted-keys/trusted_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071585759056,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:176",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585739696,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071585759056,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int datablob_parse(char * * datablob, struct trusted_key_payload * p)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585986944,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_core.c:73",
      "file": "security/keys/trusted-keys/trusted_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:trusted_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446744071586005888,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:176",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986944,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071586005888,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495116152,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446603336495121880,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495116152,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446603336495121880,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228502788,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 3228510296,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228502788,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 3228510296,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289018336,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 13835058055289027968,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289018336,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 13835058055289027968,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274370108,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 18446743936274375318,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274370108,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446743936274375318,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583334144,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334144,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071583341568,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071583347359,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271248,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271248,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071583278672,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071583284463,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583317920,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317920,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071583325344,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071583331135,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
int datablob_parse(char * datablob, struct trusted_key_payload * p, struct trusted_key_options * o)
```

```json
{
  "name": "datablob_parse",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412944,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/trusted.c:864",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_update",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    },
    {
      "addr": 0,
      "name": "datablob_parse",
      "external": false,
      "loc": "security/keys/encrypted-keys/encrypted.c:171",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/encrypted-keys/encrypted.c:encrypted_update",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412944,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071583420368,
      "name": "datablob_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071583426159,
      "name": "datablob_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct trusted_key_options * o</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * datablob</code> ➡️ <code>char * * datablob</code>
</li>
</ul>
</details>
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
