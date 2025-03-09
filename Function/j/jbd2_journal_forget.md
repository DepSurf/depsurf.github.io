# Function: <code>jbd2_journal_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896384,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1484",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896384,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083760,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1469",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083760,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173856,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1472",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173856,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260352,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1485",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260352,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409392,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1488",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409392,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1491",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602172,
      "name": "jbd2_journal_forget.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582599568,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1524",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703915,
      "name": "jbd2_journal_forget.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582701280,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1524",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877077,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582873952,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983556,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582980656,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1610",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299881,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583297232,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1613",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591349453,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583412528,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1618",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591292301,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583435376,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1635",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592273361,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583784704,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1654",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594055205,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584348160,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998144,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1662",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998144,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585226112,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1662",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585226112,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585459104,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1672",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585459104,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494660968,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494660968,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1060
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228104536,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228104536,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288476016,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288476016,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1384
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274024826,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274024826,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952292,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582949392,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889444,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582886544,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940900,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582938000,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int jbd2_journal_forget(handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_forget",
      "external": true,
      "loc": "fs/jbd2/transaction.c:1531",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028988,
      "name": "jbd2_journal_forget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583025888,
      "name": "jbd2_journal_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
