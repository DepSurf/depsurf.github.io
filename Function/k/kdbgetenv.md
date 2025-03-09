# Function: <code>kdbgetenv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109888,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:227",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109888,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143840,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:227",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143840,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184208,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:226",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184208,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191712,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191712,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243088,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243088,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303344,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303344,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355872,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355872,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408464,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408464,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580457232,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457232,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542704,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:228",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdbgetaddrarg",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542704,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580530608,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:228",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdbgetaddrarg",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530608,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534048,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:198",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdbgetaddrarg",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534048,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705376,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:197",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_dmesg",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdb_md",
        "kernel/debug/kdb/kdb_main.c:kdbgetaddrarg",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705376,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916464,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:249",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916464,
      "name": "kdbgetenv",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208672,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:249",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208672,
      "name": "kdbgetenv",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303024,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:249",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303024,
      "name": "kdbgetenv",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409248,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:249",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409248,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491731776,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491731776,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225680900,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225680900,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284758560,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284758560,
      "name": "kdbgetenv",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426032,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426032,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580373104,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373104,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417280,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417280,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * kdbgetenv(const char * match)
```

```json
{
  "name": "kdbgetenv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472864,
      "name": "kdbgetenv",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:229",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_main.c:kdbgetulenv",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472864,
      "name": "kdbgetenv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
char * kdbgetenv(const char * match)
```
</details>
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
