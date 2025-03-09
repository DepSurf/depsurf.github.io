# Function: <code>number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990528,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:392",
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
      "addr": 18446744071582990528,
      "name": "number.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272640,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:399",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272640,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391392,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:399",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391392,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588247344,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:400",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247344,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588798768,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:402",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:clock",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588798768,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176864,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:411",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:pointer_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176864,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589406784,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:412",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:pointer_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589406784,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589862672,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589862672,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088480,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088480,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086400,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:419",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086400,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585235520,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:422",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585235520,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118336,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:448",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118336,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567392,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:449",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567392,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721088,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:454",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721088,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1133
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595883744,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:455",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595883744,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596401152,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:455",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596401152,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597296256,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:457",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:format_flags",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597296256,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503866800,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503866800,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236500972,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:special_hex_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236500972,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297726768,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297726768,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279762680,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279762680,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589690736,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589690736,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589416528,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416528,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590134112,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590134112,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
```

```json
{
  "name": "number",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590184496,
      "name": "number",
      "external": false,
      "loc": "lib/vsprintf.c:416",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:bstr_printf",
        "lib/vsprintf.c:vsnprintf",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:date_str",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184496,
      "name": "number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
char * number(char * buf, char * end, long long unsigned int num, struct printf_spec spec)
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
