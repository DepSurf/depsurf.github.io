# Function: <code>ima_parse_buf</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583019024,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:176",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019024,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184048,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:176",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184048,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390448,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:178",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390448,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:178",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510933,
      "name": "ima_parse_buf.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583510224,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698549,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583697808,
      "name": "ima_parse_buf",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807042,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583806000,
      "name": "ima_parse_buf",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:179",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201451,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584200304,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:179",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591370500,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584318752,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:179",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591313192,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584353328,
      "name": "ima_parse_buf",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:219",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592309551,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071584745200,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:241",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594091868,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585424576,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:241",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596102823,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586179840,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:241",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596625935,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586417520,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:241",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597531549,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586682512,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495609864,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495609864,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228970084,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228970084,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289724848,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289724848,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274771260,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274771260,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775778,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583774736,
      "name": "ima_parse_buf",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712834,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583711792,
      "name": "ima_parse_buf",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759538,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583758496,
      "name": "ima_parse_buf",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```

```json
{
  "name": "ima_parse_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_parse_buf",
      "external": true,
      "loc": "security/integrity/ima/ima_template_lib.c:181",
      "file": "security/integrity/ima/ima_template_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860530,
      "name": "ima_parse_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583859488,
      "name": "ima_parse_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ima_parse_buf(void * bufstartp, void * bufendp, void * * bufcurp, int maxfields, struct ima_field_data * fields, int * curfields, long unsigned int * len_mask, int enforce_mask, char * bufname)
```
</details>
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
