# Function: <code>audit_log_config_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033632,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:285",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033632,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066192,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:283",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066192,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106416,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:289",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106416,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111824,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111824,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164304,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:354",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164304,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224160,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:397",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224160,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276544,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:393",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276544,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327520,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327520,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376320,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376320,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449120,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:381",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449120,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437712,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:386",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437712,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580441440,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:386",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441440,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580606272,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:386",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606272,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810608,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:388",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810608,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096624,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:386",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096624,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188256,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:386",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188256,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294448,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:386",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_set_enabled",
        "kernel/audit.c:audit_set_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294448,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491642024,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491642024,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225594132,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225594132,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284637984,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284637984,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272037368,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272037368,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580345120,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345120,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292288,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292288,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336368,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336368,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int audit_log_config_change(char * function_name, u32 new, u32 old, int allow_changes)
```

```json
{
  "name": "audit_log_config_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391600,
      "name": "audit_log_config_change",
      "external": false,
      "loc": "kernel/audit.c:380",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_do_config_change",
        "kernel/audit.c:audit_do_config_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391600,
      "name": "audit_log_config_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
