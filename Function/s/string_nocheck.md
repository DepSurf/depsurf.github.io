# Function: <code>string_nocheck</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589865824,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589865824,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590091632,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091632,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585105134,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:601",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585254318,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:604",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585137855,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:630",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585588252,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:631",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586744016,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:636",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595907614,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596425342,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597320702,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:639",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:string"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503870200,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503870200,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236496912,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
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
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236496912,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297731552,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297731552,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279765542,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279765542,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589693888,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589693888,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589419680,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419680,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590137264,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137264,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```

```json
{
  "name": "string_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590187648,
      "name": "string_nocheck",
      "external": false,
      "loc": "lib/vsprintf.c:598",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:ip4_addr_string_sa",
        "lib/vsprintf.c:ip6_addr_string_sa",
        "lib/vsprintf.c:ip4_addr_string",
        "lib/vsprintf.c:ip6_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:symbol_string",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:string",
        "lib/vsprintf.c:check_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590187648,
      "name": "string_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
char * string_nocheck(char * buf, char * end, const char * s, struct printf_spec spec)
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
