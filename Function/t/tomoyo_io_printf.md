# Function: <code>tomoyo_io_printf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419184,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:274",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_print_config",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419184,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640096,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:274",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640096,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733232,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:274",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733232,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582825776,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:274",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582825776,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982608,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:275",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982608,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182928,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:275",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182928,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299248,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:275",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299248,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486688,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071583500274,
      "name": "tomoyo_io_printf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583592672,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592672,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948496,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948496,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068336,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068336,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094880,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094880,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469280,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469280,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585105408,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:268",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585105408,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585829504,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:268",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585829504,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586061504,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:268",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586061504,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586310512,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:269",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_select_domain",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310512,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495372112,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495372112,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228749164,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228749164,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289388288,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289388288,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274577736,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274577736,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561408,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561408,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583498464,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583498464,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583545184,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545184,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void tomoyo_io_printf(struct tomoyo_io_buffer * head, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_io_printf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643712,
      "name": "tomoyo_io_printf",
      "external": false,
      "loc": "security/tomoyo/common.c:277",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_print_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643712,
      "name": "tomoyo_io_printf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
