# Function: <code>string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582988384,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:511",
      "file": "lib/vsprintf.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:bstr_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988384,
      "name": "string.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275408,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:583",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275408,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394160,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:583",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394160,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588250048,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:584",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588250048,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588801664,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:586",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588801664,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589179920,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:595",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179920,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589410032,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:596",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410032,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866352,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866352,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590092160,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092160,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093968,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:684",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093968,
      "name": "string",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585243088,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:687",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585243088,
      "name": "string",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585128624,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:713",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:fourcc_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585128624,
      "name": "string",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578368,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:714",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:fourcc_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578368,
      "name": "string",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586733488,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:719",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:fourcc_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733488,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595896384,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:720",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:fourcc_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595896384,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596413920,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:720",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:fourcc_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596413920,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597309200,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:722",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:fwnode_full_name_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:fourcc_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597309200,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503870760,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503870760,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236497464,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236497464,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297732288,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297732288,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279766020,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279766020,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589694416,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589694416,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589420208,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420208,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590137792,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137792,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590188176,
      "name": "string",
      "external": false,
      "loc": "lib/vsprintf.c:662",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590188176,
      "name": "string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
char * string(char * buf, char * end, const char * s, struct printf_spec spec)
```
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
