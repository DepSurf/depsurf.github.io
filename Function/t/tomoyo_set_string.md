# Function: <code>tomoyo_set_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582419120,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:256",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419120,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582640032,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:256",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640032,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582733168,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:256",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733168,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582825728,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:256",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582825728,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982560,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:257",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982560,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583182880,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:257",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182880,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583299200,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:257",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299200,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583500255,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486640,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583500255,
      "name": "tomoyo_set_string.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583592624,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592624,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583951653,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584071493,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584098037,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_policy",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584485549,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585120493,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:250",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585844829,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:250",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586076813,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:250",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586325821,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:251",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
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
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495371800,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495371800,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228748912,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228748912,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289388208,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289388208,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274577642,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274577642,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583561360,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561360,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583498416,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583498416,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583545136,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545136,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```

```json
{
  "name": "tomoyo_set_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583643664,
      "name": "tomoyo_set_string",
      "external": false,
      "loc": "security/tomoyo/common.c:259",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_exception",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_group",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_print_entry",
        "security/tomoyo/common.c:tomoyo_set_group",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_print_condition",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_read_profile",
        "security/tomoyo/common.c:tomoyo_io_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643664,
      "name": "tomoyo_set_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer * head, const char * string)
```
</details>
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
