# Function: <code>check_pointer</code>

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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589865920,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589865920,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590091728,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091728,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585101688,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:669",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585092176,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585250882,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:672",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241296,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585130018,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:698",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585126640,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585580423,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576384,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735928,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:704",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731136,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595898952,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:705",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595893984,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596416456,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:705",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596411424,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597311816,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:707",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ],
      "caller_func": [
        "lib/vsprintf.c:fwnode_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:fourcc_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:hex_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597306704,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503870312,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503870312,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236497036,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:resource_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236497036,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297731664,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297731664,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279765624,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279765624,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589693984,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589693984,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589419776,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419776,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590137360,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137360,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "check_pointer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590187744,
      "name": "check_pointer",
      "external": false,
      "loc": "lib/vsprintf.c:647",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:rtc_str",
        "lib/vsprintf.c:address_val",
        "lib/vsprintf.c:netdev_bits",
        "lib/vsprintf.c:uuid_string",
        "lib/vsprintf.c:escaped_string",
        "lib/vsprintf.c:ip_addr_string",
        "lib/vsprintf.c:mac_address_string",
        "lib/vsprintf.c:hex_string",
        "lib/vsprintf.c:file_dentry_name",
        "lib/vsprintf.c:dentry_name",
        "lib/vsprintf.c:string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590187744,
      "name": "check_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int check_pointer(char * * buf, char * end, const void * ptr, struct printf_spec spec)
```
</details>
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
