# Function: <code>drop_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485120,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1544",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485120,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669648,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1550",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669648,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757872,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1556",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757872,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811520,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1620",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811520,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961072,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1621",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961072,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147696,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1623",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147696,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582241600,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1622",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241600,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406224,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406224,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582505184,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582505184,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582809824,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1630",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582809824,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582883536,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1630",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:get_subdir",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883536,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911776,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1634",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911776,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246288,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1634",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246288,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743536,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1703",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743536,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584359952,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1702",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584359952,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584589680,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1493",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589680,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584821392,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1489",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:sysctl_mkdir_p",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821392,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494131544,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494131544,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227580436,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227580436,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287804032,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287804032,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273611968,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273611968,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473920,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473920,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411152,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411152,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464400,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464400,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void drop_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "drop_sysctl_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543648,
      "name": "drop_sysctl_table",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:1647",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:put_links",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543648,
      "name": "drop_sysctl_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
