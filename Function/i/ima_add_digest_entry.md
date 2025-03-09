# Function: <code>ima_add_digest_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582609812,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:71",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
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
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582855658,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:72",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951456,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:96",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951456,
      "name": "ima_add_digest_entry",
      "section": ".text",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001456,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:96",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001456,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165584,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:96",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165584,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:96",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371056,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583371846,
      "name": "ima_add_digest_entry.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:95",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489808,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583490614,
      "name": "ima_add_digest_entry.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675872,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583676778,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782944,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583783866,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173760,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071584174509,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292656,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071591369558,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326400,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071591312244,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713856,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071592308044,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585388192,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071594090367,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586140624,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140624,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586378448,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586378448,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586642992,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:93",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586642992,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495586448,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495586448,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228947320,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228947320,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289686016,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289686016,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274751502,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274751502,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751680,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583752602,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688736,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583689658,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735456,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583736378,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```

```json
{
  "name": "ima_add_digest_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_add_digest_entry",
      "external": false,
      "loc": "security/integrity/ima/ima_queue.c:94",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_restore_measurement_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836400,
      "name": "ima_add_digest_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583837306,
      "name": "ima_add_digest_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int ima_add_digest_entry(struct ima_template_entry * entry, bool update_htable)
```
</details>
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
